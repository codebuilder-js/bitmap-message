# 🖼️ Bitmap Message Renderer

Este é um pequeno script Python que imprime uma mensagem personalizada no formato de um "bitmap" artístico feito com caracteres. A ideia é substituir os caracteres `*` da imagem original por letras de uma mensagem fornecida pelo usuário, criando um efeito visual interessante.

## 📜 Descrição

O código utiliza uma arte em ASCII como base (armazenada na string `bitmap`) e pede ao usuário uma mensagem. Em seguida, substitui os asteriscos `*` pela mensagem, repetindo os caracteres conforme necessário, para preencher a imagem com o texto.

### Exemplo de uso

```bash
$ python bitmap_message.py
Enter the message to display in the bitmap.
> Hello
```

Saída (exemplo simplificado):

```
   HelloHelloHe   H  ell oH  e      HelloHelloHelloHelloHelloHello
  ...
```

## 🧠 Como funciona

1. O bitmap é armazenado como uma string multilinha com `*` formando uma figura.
2. O usuário digita uma mensagem.
3. O script percorre cada linha do bitmap:

   * Se encontrar um espaço, imprime um espaço.
   * Se encontrar um `*`, imprime um caractere da mensagem, repetindo se necessário.

## ⚙️ Requisitos

* Python 3

## 🚀 Execução

Para executar o script:

```bash
python bitmap_message.py
```

## 🛑 Cancelamento

Se o usuário pressionar Enter sem digitar uma mensagem, o programa encerra automaticamente com `sys.exit()`.

## 🧪 Teste Rápido

Você pode alterar o conteúdo do bitmap ou modificar o comportamento para criar efeitos diferentes com outras mensagens ou figuras.

## 📄 Licença

Este projeto é livre para uso educacional e pessoal.
