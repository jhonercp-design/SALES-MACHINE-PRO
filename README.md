# SALES MACHINE PRO 🚀

**Plataforma Inteligente de Planejamento e Gestão de Vendas com IA**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-v1.0.0-brightgreen)]()
[![Built with](https://img.shields.io/badge/built%20with-React%2C%20TypeScript%2C%20Vite-blue)]()

## 📋 Visão Geral

**Sales Machine Pro** é uma plataforma inovadora de gestão de vendas que utiliza inteligência artificial para otimizar planejamento estratégico, análise de metas e previsões de faturamento. Com recursos avançados como análise de peso semanal, integração de feriados regionalizados e KPIs em tempo real, oferece aos empresários uma visão clara e acionável do desempenho de vendas.

## ✨ Principais Features

### 1. **Peso Semanal Estratégico** 🎯
- Seleção regionalizada de até 5 estados
- - Cálculo inteligente de faturamento por estado
  - - Motor de feriados nacionais e estaduais
    - - Lógica de emendas (pontes) automática
      - - Visualização anual com 52 semanas
       
        - ### 2. **Dashboard Inteligente** 📊
        - - KPIs em tempo real
          - - Gráficos interativos
            - - Filtros avançados
              - - Exportação de relatórios
               
                - ### 3. **Gestão de Metas e Projetos** 💼
                - - Pipeline de vendas customizável
                  - - Rastreamento de projetos
                    - - Sistema de notificações
                     
                      - ### 4. **Análise de Conversão** 📈
                      - - Métricas de funil de vendas
                        - - Taxa de conversão por canal
                          - - Insights de performance
                           
                            - ## 🛠️ Stack Tecnológico
                           
                            - - **Frontend**: React 18.x + TypeScript
                              - - **Build Tool**: Vite
                                - - **UI Components**: Recharts (gráficos), Tailwind CSS
                                  - - **State Management**: Context API
                                    - - **Armazenamento**: LocalStorage (com plano para backend)
                                      - - **Linguagem**: TypeScript 5.x
                                       
                                        - ## 📦 Estrutura do Projeto
                                       
                                        - ```
                                          SALES-MACHINE-PRO/
                                          ├── src/
                                          │   ├── components/          # Componentes React
                                          │   │   ├── AdvancedModules.tsx
                                          │   │   ├── Modules.tsx      # Módulo principal (~1500+ linhas)
                                          │   │   ├── WeeklyWeightModule.tsx  # Novo módulo inteligente
                                          │   │   ├── DashboardModule.tsx
                                          │   │   ├── ProductsModule.tsx
                                          │   │   ├── CalculadorasModule.tsx
                                          │   │   ├── MetodologiaModule.tsx
                                          │   │   ├── TrilhaModule.tsx
                                          │   │   ├── FilterBar.tsx
                                          │   │   └── [outros componentes]
                                          │   ├── contexts/            # Context API
                                          │   │   └── AppContext.tsx
                                          │   ├── hooks/               # Custom hooks
                                          │   │   └── useLocalStorage.ts
                                          │   ├── services/            # Serviços e utilitários
                                          │   │   ├── reportService.ts
                                          │   │   └── types.ts
                                          │   ├── App.tsx              # Componente raiz
                                          │   ├── main.tsx             # Entry point
                                          │   └── index.css            # Estilos globais
                                          ├── public/                  # Arquivos estáticos
                                          ├── package.json             # Dependências
                                          ├── tsconfig.json            # Config TypeScript
                                          ├── vite.config.ts           # Config Vite
                                          ├── .env.example             # Variáveis de ambiente
                                          └── .gitignore               # Git ignore rules
                                          ```

                                          ## 🚀 Quick Start

                                          ### Pré-requisitos
                                          - Node.js 16+ ou superior
                                          - - npm ou yarn
                                           
                                            - ### Instalação
                                           
                                            - 1. **Clone o repositório**
                                              2. ```bash
                                                 git clone https://github.com/jhonercp-design/SALES-MACHINE-PRO.git
                                                 cd SALES-MACHINE-PRO
                                                 ```

                                                 2. **Instale as dependências**
                                                 3. ```bash
                                                    npm install
                                                    ```

                                                    3. **Configure variáveis de ambiente**
                                                    4. ```bash
                                                       cp .env.example .env.local
                                                       ```

                                                       4. **Inicie o servidor de desenvolvimento**
                                                       5. ```bash
                                                          npm run dev
                                                          ```

                                                          5. **Acesse no navegador**
                                                          6. ```
                                                             http://localhost:5173
                                                             ```

                                                             ## 📖 Documentação Adicional

                                                             - **[SETUP.md](./SETUP.md)** - Guia de instalação detalhado
                                                             - - **[DEPLOYMENT.md](./DEPLOYMENT.md)** - Deploy no Vercel e produção
                                                               - - **[SECURITY.md](./SECURITY.md)** - Recomendações de segurança
                                                                 - - **[ARCHITECTURE.md](./ARCHITECTURE.md)** - Arquitetura do projeto
                                                                  
                                                                   - ## 🔍 Análise de Segurança (v1.0)
                                                                  
                                                                   - ### ✅ Pontos Fortes
                                                                   - - Compilação TypeScript sem erros (100% sucesso)
                                                                     - - Proteção contra XSS implementada
                                                                       - - Sem uso de `dangerouslySetInnerHTML` ou `eval()`
                                                                        
                                                                         - ### ⚠️ Áreas de Melhoria
                                                                         - - [ ] Remover console.log de debug em produção
                                                                           - [ ] - [ ] Implementar criptografia para localStorage
                                                                           - [ ] - [ ] Refatorar `Modules.tsx` (1500+ linhas)
                                                                           - [ ] - [ ] Adicionar otimizações de render (useMemo, useCallback)
                                                                           - [ ] - [ ] Conectar backend para validação de dados
                                                                          
                                                                           - [ ] Veja [SECURITY.md](./SECURITY.md) para detalhes.
                                                                          
                                                                           - [ ] ## 🎯 Roadmap
                                                                          
                                                                           - [ ] ### v1.0 (Atual)
                                                                           - [ ] - ✅ Dashboard principal
                                                                           - [ ] - ✅ Módulo de peso semanal
                                                                           - [ ] - ✅ KPIs e metas
                                                                           - [ ] - ✅ Gestão de projetos
                                                                          
                                                                           - [ ] ### v1.1 (Próximo)
                                                                           - [ ] - [ ] Backend API (Node.js + Express)
                                                                           - [ ] - [ ] Banco de dados (PostgreSQL)
                                                                           - [ ] - [ ] Autenticação melhorada
                                                                           - [ ] - [ ] Sistema de permissões
                                                                          
                                                                           - [ ] ### v2.0
                                                                           - [ ] - [ ] Mobile app (React Native)
                                                                           - [ ] - [ ] Integrações com CRM
                                                                           - [ ] - [ ] IA para previsões de vendas
                                                                           - [ ] - [ ] Relatórios PDF automáticos
                                                                          
                                                                           - [ ] ## 📱 Deployment
                                                                          
                                                                           - [ ] ### Vercel (Recomendado)
                                                                           - [ ] A forma mais rápida de fazer deploy:
                                                                          
                                                                           - [ ] ```bash
                                                                           - [ ] npm install -g vercel
                                                                           - [ ] vercel
                                                                           - [ ] ```
                                                                          
                                                                           - [ ] Ou conecte seu repositório GitHub ao Vercel via dashboard.
                                                                          
                                                                           - [ ] Veja [DEPLOYMENT.md](./DEPLOYMENT.md) para instruções passo-a-passo.
                                                                          
                                                                           - [ ] ## 🤝 Contribuindo
                                                                          
                                                                           - [ ] Contribuições são bem-vindas! Por favor:
                                                                          
                                                                           - [ ] 1. Faça um Fork
                                                                           - [ ] 2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
                                                                           - [ ] 3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
                                                                           - [ ] 4. Push para a branch (`git push origin feature/AmazingFeature`)
                                                                           - [ ] 5. Abra um Pull Request
                                                                          
                                                                           - [ ] ## 📄 Licença
                                                                          
                                                                           - [ ] Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](./LICENSE) para detalhes.
                                                                          
                                                                           - [ ] ## 👥 Autor
                                                                          
                                                                           - [ ] **Jhonercp Design**
                                                                           - [ ] GitHub: [@jhonercp-design](https://github.com/jhonercp-design)
                                                                          
                                                                           - [ ] ## 📞 Suporte
                                                                          
                                                                           - [ ] Para dúvidas ou sugestões:
                                                                           - [ ] - 📧 Email: contato@seusite.com
                                                                           - [ ] - 💬 Issues no GitHub: [GitHub Issues](https://github.com/jhonercp-design/SALES-MACHINE-PRO/issues)
                                                                          
                                                                           - [ ] ## 🙏 Agradecimentos
                                                                          
                                                                           - [ ] Desenvolvido com ♥ para otimizar a gestão de vendas no Brasil.
                                                                          
                                                                           - [ ] ---
                                                                          
                                                                           - [ ] **Versão**: 1.0.0 | **Última atualização**: Março 2026
