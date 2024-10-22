# Pi-hole: Network-wide Ad Blocking

## What is Pi-hole?

Pi-hole is a DNS sinkhole designed to protect your devices from unwanted content without installing any client-side software. It serves as a network-wide ad blocker on your own Linux hardware, offering a lightweight and responsive way to improve browsing speed and enhance privacy.

### Key Features of Pi-hole

- **Easy-to-install**: The setup process is straightforward, usually completed in less than ten minutes.
- **Resolute**: Blocks content in non-browser locations, such as ad-laden mobile apps and smart TVs.
- **Responsive**: Enhances the browsing experience by efficiently caching DNS queries.
- **Lightweight**: Operates smoothly with minimal hardware and software requirements.
- **Robust**: Features a quality-assured command-line interface for reliable interoperability.
- **Insightful**: Includes a beautifully designed Web Interface that allows for comprehensive monitoring and control of your Pi-hole.
- **Versatile**: Optionally functions as a DHCP server, providing protection across all devices automatically.
- **Scalable**: Handles hundreds of millions of queries on server-grade hardware.
- **Modern**: Supports both IPv4 and IPv6, ensuring comprehensive ad-blocking.
- **Free**: Pi-hole is open source, putting control of your online privacy in your hands.

# Pi-hole Project (English)

## What is Pi-hole?
Pi-hole is a network-wide ad blocker that acts as a DNS sinkhole, blocking ads and trackers at the network level. This improves browsing speed and enhances user privacy.

### Features
- Blocks unwanted content: Ads, trackers, and malware.
- Lightweight: Can run on low-power devices like Raspberry Pi.
- User-friendly web interface for easy management.
- Customizable with adlists that enhance blocking capabilities.

### Installation Instructions
#### System Requirements:
- Raspberry Pi (or any Linux-based device).
- A stable internet connection.

#### Installation Steps:
1. Open the terminal on your Raspberry Pi or SSH into it.
2. Run the following command to download and execute the Pi-hole installer:
   ```bash
   curl -sSL https://install.pi-hole.net | bash
#### Follow the on-screen instructions to complete the installation. You will configure settings such as the DNS provider and adlists.

### Configuration
#### Accessing the Web Interface:
- After installation, access the Pi-hole admin interface by navigating to `http://<your_pi_ip_address>/admin`.
- Log in using the password set during installation.

#### Adding Adlists:
- In the admin interface, go to **Group Management > Adlists**.
- Add the URLs of adlists in the input field and click **Add**.

#### Using Custom Adlists:
- To enhance ad blocking, you can add custom adlists. Here are a few steps:
  - Copy the URL of the adlist you wish to add.
  - Navigate to **Group Management > Adlists** in the Pi-hole admin interface.
  - Paste the URL into the input box and click **Add**.

#### Contributing Your Own Adlists:
- If you have adlists that you would like to share with the community:
  - Fork the repository where the adlists are stored.
  - Add your adlists to the designated directory.
  - Create a pull request with a description of the changes you made.
  - For any discussions or suggestions, feel free to open an issue in the repository.

### Relevant Links:
- [Pi-hole Official Website](https://pi-hole.net/)
- [Pi-hole GitHub Repository](https://github.com/pi-hole/pi-hole)
- [Pi-hole Documentation](https://docs.pi-hole.net/)
- [Pi-hole Community Forums](https://discourse.pi-hole.net/)

### Explore More About Pi-hole: Recommended Resources

**[Pi-hole Official Website](https://pi-hole.net/)**  
The official Pi-hole website is your starting point for all things Pi-hole. It offers comprehensive guides on how to install and configure the software, details on features, and ways to support the project. This is the perfect resource for beginners and experts alike who want to understand the full capabilities and foundation of Pi-hole.

**[Pi-hole GitHub Repository](https://github.com/pi-hole/pi-hole)**  
For those interested in the technical side, the Pi-hole GitHub repository is crucial. It hosts the source code, allows community contributions, and is a hub for tracking bug reports and feature requests. This platform is essential for developers looking to contribute to the project or customize their Pi-hole setup.

**[Pi-hole on Reddit](https://www.reddit.com/r/pihole/)**  
The Pi-hole subreddit is an active community forum where users share tips, seek help, and discuss their experiences with Pi-hole. It’s a great place to learn from other users' setups, find troubleshooting advice, and explore advanced configurations and hacks.

These resources provide a solid foundation for anyone looking to get involved with Pi-hole, whether it’s through using the software, contributing to its development, or engaging with the community.


---

# Projeto Pi-hole (Português)

## O que é o Pi-hole?
Pi-hole é um bloqueador de anúncios em toda a rede que atua como um sinkhole DNS, bloqueando anúncios e rastreadores em nível de rede. Isso melhora a velocidade de navegação e aumenta a privacidade do usuário.

### Recursos
- Bloqueia conteúdo indesejado: anúncios, rastreadores e malware.
- Leve: pode rodar em dispositivos de baixo consumo, como Raspberry Pi.
- Interface web amigável para fácil gerenciamento.
- Personalizável com adlists que aumentam as capacidades de bloqueio.

### Instruções de Instalação
#### Requisitos do Sistema:
- Raspberry Pi (ou qualquer dispositivo baseado em Linux).
- Uma conexão estável à internet.

#### Passos de Instalação:
1. Abra o terminal no seu Raspberry Pi ou acesse-o via SSH.
2. Execute o seguinte comando para baixar e executar o instalador do Pi-hole:
   ```bash
   curl -sSL https://install.pi-hole.net | bash

### Explore Mais Sobre o Pi-hole: Recursos Recomendados

**[Site Oficial do Pi-hole](https://pi-hole.net/)**  
O site oficial do Pi-hole é seu ponto de partida para tudo relacionado ao Pi-hole. Oferece guias completos sobre como instalar e configurar o software, detalhes sobre recursos e formas de apoiar o projeto. Este é o recurso perfeito para iniciantes e especialistas que desejam entender as capacidades completas e a base do Pi-hole.

**[Repositório do Pi-hole no GitHub](https://github.com/pi-hole/pi-hole)**  
Para aqueles interessados no lado técnico, o repositório do Pi-hole no GitHub é crucial. Ele hospeda o código-fonte, permite contribuições da comunidade e é um centro para rastreamento de relatórios de bugs e solicitações de funcionalidades. Esta plataforma é essencial para desenvolvedores que procuram contribuir com o projeto ou personalizar sua configuração do Pi-hole.

**[Pi-hole no Reddit](https://www.reddit.com/r/pihole/)**  
O subreddit do Pi-hole é uma comunidade ativa onde os usuários compartilham dicas, buscam ajuda e discutem suas experiências com o Pi-hole. É um ótimo lugar para aprender com as configurações de outros usuários, encontrar conselhos para solução de problemas e explorar configurações avançadas e hacks.

Esses recursos fornecem uma base sólida para qualquer pessoa que deseja se envolver com o Pi-hole, seja usando o software, contribuindo para o seu desenvolvimento ou interagindo com a comunidade.


