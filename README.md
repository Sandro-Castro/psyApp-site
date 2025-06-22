# Psyc Presentation Site

Este repositório contém o site estático de apresentação do **Psyc**, um aplicativo desenvolvido no contexto do componente curricular **"Oficina de Integração"** do IFSC - Instituto Federal de Santa Catarina. O site tem como objetivo informar visitantes sobre o projeto, destacar suas funcionalidades, tecnologias utilizadas, equipe envolvida e formas de contato.

---

## Objetivo do Site

- **Apresentar o Psyc**: Fornecer uma visão clara sobre o propósito do aplicativo, seu público-alvo (psicólogos do IFSC Campus Chapecó) e benefícios.
- **Contextualizar o Projeto**: Explicar que se trata de um Projeto Integrador desenvolvido no componente curricular "Oficina de Integração" do IFSC, unindo conhecimentos de diversas disciplinas e promovendo trabalho colaborativo.
- **Mostrar Funcionalidades e Tecnologias**: Listar recursos do aplicativo e justificar as escolhas tecnológicas adotadas durante o desenvolvimento.
- **Destacar a Equipe**: Apresentar os integrantes do projeto, seus papéis e contribuições.
- **Facilitar Contato e Engajamento**: Disponibilizar links para LinkedIn, e-mail e eventuais instruções para experimentar demo ou dar feedback.

---

## Estrutura de Arquivos

```
psyApp-site/
├── about.html            # Página "Sobre": descrição do PsyIF e contexto do projeto
├── features.html         # Página "Funcionalidades": lista de recursos em andamento
├── technologies.html     # Página "Tecnologias": tecnologias empregadas e motivos de escolha
├── team.html             # Página "Equipe": fotos, nomes, papéis e descrições de cada membro
├── contact.html          # Página "Contato": links de LinkedIn e e-mail para comunicação
├── assets/
│   ├── css/
│   │   └── style.css     # Estilos customizados 
│   └── images/
│       ├── logo.png      # Logo do Psyc
│       ├── member1.jpg   # Fotos dos integrantes 
│       ├── member2.jpg
│       ├── member3.jpg
│       ├── member4.jpg
│       ├── member5.jpg
│       └── member6.jpg
└── README.md             # Este arquivo de documentação
```


## Conteúdo das Páginas

1. **Sobre (about.html)**
   - Explica o que é o Psyc: aplicativo para psicólogos do IFSC Campus Chapecó.
   - Contextualiza o Projeto Integrador na "Oficina de Integração" do IFSC, enfatizando o caráter colaborativo e interdisciplinar.
   - Destaca benefícios: interface intuitiva, registro de sessões, geração de relatórios, análise de métricas, segurança e conformidade com LGPD.
   - Menciona possíveis integrações futuras: teleconsulta, dashboards avançados, app web para pacientes, notificações.

2. **Funcionalidades (features.html)**
   - Lista as principais funcionalidades em andamento, com cards contendo título, descrição e badge "Em andamento".
   - Exemplos: cadastro seguro de pacientes, autenticação, gravação e transcrição automática, geração de relatórios, histórico completo, consentimento digital, envio de e-mail, relatórios gerais e individuais, pagamentos/assinaturas, teleconsulta (futuro), app web para pacientes, notificações push.

3. **Tecnologias (technologies.html)**
   - Lista cada tecnologia usada e motivações:
     - Expo & React Native: desenvolvimento mobile multiplataforma.
     - TypeScript: tipagem estática e manutenibilidade.
     - .NET 9 & C#: backend robusto.
     - Entity Framework Core: ORM para MySQL.
     - MySQL: banco relacional open-source.
     - Hugging Face Transformers & Whisper: IA para transcrição e summarization.
     - JWT: autenticação stateless.
     - AutoMapper: mapeamento de entidades e DTOs.
     - Axios: requisições HTTP do front.
     - Bootstrap 5: estilo do site estático.
     - GitHub Pages.
     - GitHub Actions: CI/CD.

4. **Equipe (team.html)**
   - Apresenta foto, nome, papel e breve descrição de cada membro.
   - LinkedIn de cada integrante.
   - Destaca que o projeto é conjunto, integrando conhecimentos de frontend, backend, IA, DevOps, UX/UI, gestão de projeto e testes.

5. **Contato (contact.html)**
   - Fornece link para LinkedIn do responsável ou equipe.
   - Exibe e-mail de contato: `aDefinir@aDefinir@gmail.com`.
   - (Opcional) Formulário de contato via Formspree ou similar, se desejado.

---

## Contexto Acadêmico

- Este site faz parte do Projeto Integrador desenvolvido no componente curricular **"Oficina de Integração"** do IFSC - Instituto Federal de Santa Catarina.
- O objetivo do componente é aplicar conhecimentos adquiridos em diferentes disciplinas para criar uma solução prática e relevante.
- O Psyc exemplifica esse objetivo, integrando desenvolvimento mobile, backend, IA, segurança de dados, usabilidade e gestão de projeto.
- A experiência colaborativa fortalece competências técnicas e interpessoais dos alunos, alinhada às demandas reais de mercado.

---

> **Observação:** Este site é uma interface informativa sobre o aplicativo PsyIF e não contém funcionalidades dinâmicas do app em si. Para testar o aplicativo, consulte o repositório e siga as instruções de setup para rodar a demo via Expo ou instalação de APK.

