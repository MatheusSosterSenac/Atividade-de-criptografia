Chaves Assimétricas:

Utilizamos uma chave pública para criptografar mensagens e uma chave privada para descriptografá-las para que apenas quem possui a chave privada possa acessar a mensagem original.

HTML:

São 2 páginas, uma para criptografar e outra para descriptografar.
Cada página contém um formulário onde o usuário pode inserir a mensagem ou o texto criptografado.

Criptografia:
Na página de criptografia, a função encryptMessage utiliza a chave pública para transformar a mensagem inserida pelo usuário em texto criptografado.

Descriptografia:
Na página de descriptografia, a função decryptMessage utiliza a chave privada para reverter o texto criptografado à sua forma original.

Para usar:

O usuário acessa a página de criptografia, insere uma mensagem e clica no botão para criptografar, o resultado é exibido em um campo de texto e então navega para a página de descriptografia, 
insere o texto criptografado e clica no botão para descriptografar, e a mensagem original é exibida em outro campo de texto.
