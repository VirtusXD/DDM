# Está Aberto - Aplicativo para informação e avaliações.
## 👨‍💻Professor responsável
* Carlos  Eduardo Duque Polito 
## 🎯Objetivo do App 
O objetivo é fornecer uma plataforma onde os usuários possam avaliar e verificar o status de funcionamento dos comércios. Mantendo o público atualizado sobre os horários e qualidade do local.
## 👤Público-alvo
Destinado aos consumidores locais que buscam informações sobre estabelecimentos antes de visitá-los ou aos que desejam avalia-los. Também pode interessar a donos de comércios, que desejam acompanhar a reputação de seus negócios.
## ❌Não é o objetivo
* Comércio local online
* Anúncio em geral
## Dícionário de Dados

# Diagramas UML

## Mockup do APP
![AppAvaliações](https://github.com/user-attachments/assets/eec4dc52-6c71-47b0-8438-655b9bb41a8b)

## Digrama de Classes
![Diagrama em branco](https://github.com/user-attachments/assets/3f6a9605-98db-48b2-8b76-8e73968a8a60)

## Diagrama Caso de Uso
![Diagrama de caso de uso](https://github.com/user-attachments/assets/e81a2a9b-9be0-41fd-ab42-85a3bfc3c1e7)

## Diagrama Atividade
![Diagrama de atividade](https://github.com/user-attachments/assets/932e9f22-f3ed-4454-8e1d-a35bcc67ff36)

# 📊Plano de Capacidade

### Estimativa de Espaço

usuarios ~3 KB (id, name, email, img_url, creat_at);

comercios	~4 KB (id, name,address, category, operating_time, img_url, id_avaliacao);

avaliacoes	~2 KB (id, id_user, id_comercio, commentary, rating, creat_at).

Total estimado:  < 15 Kb's

# Estratégia de Backup e Recuperação

### Backup de Dados em GitHub
Utilizaremos o próprio GitHub para efetuar o Backup

Vantagens:
- Versátil;
- Possível fazer Bkp automático;
- Gratuito;

Configuração do Repositório:

- Criar diretório padrão privado (+ seguro)

- Tamanho Backup: O GitHub tem limites para o tamanho de repositórios e arquivos, com limite de 100 MB por arquivo e 1 GB por repositório.



