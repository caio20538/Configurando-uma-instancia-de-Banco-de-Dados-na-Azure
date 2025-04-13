☁️ Computação em Nuvem — Modelos de Serviço & Responsabilidade Compartilhada

Este documento apresenta os principais modelos de serviço em nuvem e o conceito fundamental de responsabilidade compartilhada, utilizado por provedores como Azure, AWS e Google Cloud.
💡 Modelos de Serviço: IaaS, PaaS e SaaS

Na computação em nuvem, existem três modelos principais de serviço que definem o quanto a responsabilidade técnica é do cliente ou do provedor.
🏗️ IaaS — Infrastructure as a Service

    Infraestrutura como Serviço

O provedor de nuvem oferece recursos básicos como servidores, armazenamento e redes. O cliente é responsável por instalar, configurar e manter o sistema operacional, middlewares e aplicações.

Exemplos:
Azure Virtual Machines, Amazon EC2, Google Compute Engine.

✅ Flexível e escalável
❗ Manutenção e atualizações de software são de responsabilidade do cliente.
🔧 PaaS — Platform as a Service

    Plataforma como Serviço

Aqui o provedor fornece, além da infraestrutura, o ambiente de desenvolvimento completo, incluindo sistemas operacionais, servidores de aplicação e banco de dados gerenciado. O cliente foca apenas na lógica da aplicação.

Exemplos:
Azure App Service, Heroku, Google App Engine.

✅ Sem preocupações com hardware ou sistemas operacionais
❗ Customização da plataforma é limitada.
🧑‍💻 SaaS — Software as a Service

    Software como Serviço

Tudo é gerenciado pelo provedor: hardware, software, banco de dados e rede. O cliente apenas utiliza o serviço através de uma interface, normalmente via navegador.

Exemplos:
Microsoft 365, Google Workspace, Salesforce.

✅ Uso imediato, sem necessidade de instalação ou manutenção
❗ Personalização e controle sobre o ambiente são limitados.
🔐 Modelo de Responsabilidade Compartilhada

A segurança e operação em nuvem seguem o modelo de responsabilidade compartilhada, que determina quais tarefas são do provedor e quais são do cliente.
Responsável	Cliente	Provedor de Nuvem
Dados	✅	
Controle de Identidade e Acesso	✅	
Sistema Operacional	✅ (IaaS)	✅ (PaaS/SaaS)
Aplicação	✅ (IaaS/PaaS)	✅ (SaaS)
Banco de Dados	✅ (IaaS)	✅ (PaaS/SaaS)
Virtualização		✅
Hardware		✅
Rede Física e Data Center		✅

👉 Em resumo:

    O cliente é responsável pelo que controla (dados, acessos, aplicações).

    O provedor garante a segurança e disponibilidade da infraestrutura física e virtual.
