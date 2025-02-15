<template>
  <div>
    <!-- Seção Hero -->
    <section class="hero">
      <h1>Impulsione Seu Negócio com Marketing Digital</h1>
      <p>Tráfego pago, social media e publicidade para expandir sua marca.</p>
      <a href="#contato" class="btn">Solicite um Orçamento</a>
    </section>

    <!-- Seção Sobre -->
    <section class="sobre">
      <h2>Sobre a Agência</h2>
      <p>Somos especialistas em criar estratégias de marketing digital que geram resultados.</p>
    </section>

    <!-- Seção Serviços -->
    <section class="servicos">
      <h2>Nossos Serviços</h2>
      <ul>
        <li>🚀 Gestão de Tráfego Pago</li>
        <li>📱 Social Media</li>
        <li>🎨 Design Gráfico</li>
        <li>📊 Consultoria Estratégica</li>
      </ul>
    </section>

    <!-- Seção Contato -->
    <section id="contato" class="contato">
      <h2>Fale Conosco</h2>
      <form name="contato" method="POST" netlify>
        <input type="text" name="nome" placeholder="Seu Nome" required>
        <input type="email" name="email" placeholder="Seu E-mail" required>
        <textarea name="mensagem" placeholder="Sua Mensagem" required></textarea>
        <button type="submit">Enviar</button>
      </form>
      <a href="https://wa.me/seu-numero" class="btn-whatsapp">Fale pelo WhatsApp</a>
    </section>
  </div>
</template>

<style>
/* Estilos básicos */
.hero { text-align: center; padding: 50px; background: #f8f9fa; }
.sobre, .servicos, .contato { padding: 40px; text-align: center; }
.servicos ul { list-style: none; padding: 0; }
.servicos li { font-size: 18px; margin: 10px 0; }
.btn { display: inline-block; padding: 10px 20px; background: #007BFF; color: #fff; text-decoration: none; border-radius: 5px; }
.btn-whatsapp { display: inline-block; margin-top: 20px; background: #25d366; padding: 10px 20px; border-radius: 5px; color: white; text-decoration: none; }
</style>
