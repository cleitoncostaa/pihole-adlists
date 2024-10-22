Pi-hole Project (English)
What is Pi-hole? Pi-hole is a network-wide ad blocker that acts as a DNS sinkhole, blocking ads and trackers at the network level. This improves browsing speed and enhances user privacy.

Features:
Blocks unwanted content: Ads, trackers, and malware.
Lightweight: Can run on low-power devices like Raspberry Pi.
User-friendly web interface for easy management.
Customizable with adlists that enhance blocking capabilities.
Installation Instructions:
System Requirements:

Raspberry Pi (or any Linux-based device).
A stable internet connection.
Installation Steps:

Open the terminal on your Raspberry Pi or SSH into it.
Run the following command to download and execute the Pi-hole installer:
bash
Copiar código
curl -sSL https://install.pi-hole.net | bash
Follow the on-screen instructions to complete the installation. You will configure settings such as the DNS provider and adlists.
Configuration:
Accessing the Web Interface:

After installation, access the Pi-hole admin interface by navigating to http://<your_pi_ip_address>/admin.
Log in using the password set during installation.
Adding Adlists:

In the admin interface, go to Group Management > Adlists.
Add the URLs of adlists in the input field and click Add.
Using Custom Adlists:
To enhance ad blocking, you can add custom adlists. Here are a few steps:
Copy the URL of the adlist you wish to add.
Navigate to Group Management > Adlists in the Pi-hole admin interface.
Paste the URL into the input box and click Add.
Contributing Your Own Adlists:
If you have adlists that you would like to share with the community:
Fork the repository where the adlists are stored.
Add your adlists to the designated directory.
Create a pull request with a description of the changes you made.
For any discussions or suggestions, feel free to open an issue in the repository.
Relevant Links:
Pi-hole Official Website
Pi-hole GitHub Repository
Pi-hole Documentation
Pi-hole Community Forums

---

Projeto Pi-hole (Português)
O que é o Pi-hole? Pi-hole é um bloqueador de anúncios em toda a rede que atua como um sinkhole DNS, bloqueando anúncios e rastreadores em nível de rede. Isso melhora a velocidade de navegação e aumenta a privacidade do usuário.

Recursos:
Bloqueia conteúdo indesejado: anúncios, rastreadores e malware.
Leve: pode rodar em dispositivos de baixo consumo, como Raspberry Pi.
Interface web amigável para fácil gerenciamento.
Personalizável com adlists que aumentam as capacidades de bloqueio.
Instruções de Instalação:
Requisitos do Sistema:

Raspberry Pi (ou qualquer dispositivo baseado em Linux).
Uma conexão estável à internet.
Passos de Instalação:

Abra o terminal no seu Raspberry Pi ou acesse-o via SSH.
Execute o seguinte comando para baixar e executar o instalador do Pi-hole:
bash
Copiar código
curl -sSL https://install.pi-hole.net | bash
Siga as instruções na tela para completar a instalação. Você irá configurar definições como o provedor DNS e as adlists.
Configuração:
Acessando a Interface Web:

Após a instalação, acesse a interface de administração do Pi-hole navegando para http://<seu_ip_do_pi>/admin.
Faça login usando a senha definida durante a instalação.
Adicionando Adlists:

Na interface de administração, vá para Gerenciamento de Grupos > Adlists.
Adicione as URLs das adlists no campo de entrada e clique em Adicionar.
Usando Adlists Personalizadas:
Para melhorar o bloqueio de anúncios, você pode adicionar adlists personalizadas. Aqui estão alguns passos:
Copie a URL da adlist que você deseja adicionar.
Navegue para Gerenciamento de Grupos > Adlists na interface administrativa do Pi-hole.
Cole a URL no campo de entrada e clique em Adicionar.
Contribuindo com Suas Próprias Adlists:
Se você tiver adlists que gostaria de compartilhar com a comunidade:
Faça um fork do repositório onde as adlists estão armazenadas.
Adicione suas adlists ao diretório designado.
Crie um pull request com uma descrição das alterações que você fez.
Para qualquer discussão ou sugestões, sinta-se à vontade para abrir um issue no repositório.
Links Relevantes:
Site Oficial do Pi-hole
Repositório do Pi-hole no GitHub
Documentação do Pi-hole
Fóruns da Comunidade Pi-hole
