# meusite-whatsapp
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Contato WhatsApp e Cancelamento</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f9f9f9;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 40px 20px;
      color: #333;
    }
    h1 {
      color: #25D366;
    }
    .btn {
      display: inline-block;
      margin: 15px 10px;
      padding: 15px 30px;
      font-size: 18px;
      border-radius: 8px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      box-shadow: 0 5px 10px rgba(0,0,0,0.1);
      transition: background-color 0.3s ease;
      user-select: none;
    }
    .whatsapp-btn {
      background-color: #25D366;
    }
    .whatsapp-btn:hover {
      background-color: #1ebe57;
    }
    .cancel-btn {
      background-color: #e74c3c;
    }
    .cancel-btn:hover {
      background-color: #c0392b;
    }
    p {
      max-width: 400px;
      text-align: center;
      margin-top: 25px;
      font-size: 16px;
      line-height: 1.5;
    }
  </style>
</head>
<body>
  <h1>Fale Conosco no WhatsApp</h1>

  <a 
    href="https://wa.me/5533984297748" 
    target="_blank" 
    rel="noopener noreferrer" 
    class="btn whatsapp-btn"
  >
    📲 Falar no WhatsApp
  </a>

  <a 
    href="https://seusite.com/cancelar-assinatura?numero=5533984297748" 
    class="btn cancel-btn"
  >
    ❌ Cancelar Assinatura
  </a>

  <p>
    Clique no botão <strong>"Falar no WhatsApp"</strong> para enviar uma mensagem direta para nosso número.<br /><br />
    Se desejar cancelar sua assinatura, clique no botão <strong>"Cancelar Assinatura"</strong>. Caso não tenha um site, podemos configurar para você enviar uma mensagem automática para o WhatsApp solicitando o cancelamento.
  </p>
</body>
</html>
