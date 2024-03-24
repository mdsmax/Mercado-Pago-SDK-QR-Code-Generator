
# Mercado Pago SDK - Pix (QR Code & Copia e Cola) Generator

The script developed uses the Mercado Pago SDK to create the PIX payment. The script creates the payment with the desired amount, turns it into Copy and Paste and then creates a QR Code.

To use it, you must have a Mercado Pago account and it must be from a person over 18 years old.

How to get the **access token**: [click here to access the tutorial](https://proximaweb.com.br/tutoriais/como-gerar-o-token-do-mercadopago-e-public-key-do-marcadopago-criado-em-2020/#:~:text=Acesse%20o%20endere%C3%A7o%20https%3A%2F%2F,Cadastro%20e%20fa%C3%A7a%20seu%20Login.&text=Ao%20acessar%20este%20endere%C3%A7o%2C%20voc%C3%AA,para%20configurar%20em%20sua%20loja.)




## How To Use

Install Python, go to the terminal and type:

```py
  pip install mercadopago qrcode
```

After, go to '**config.json**', put your access token in the empty space.

Finally, you can change the amount of Pix and the e-mail in the '**index.py**'. To run, type this in the terminal:

```py
   python index.py
```
    
