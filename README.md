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
