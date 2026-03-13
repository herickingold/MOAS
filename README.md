**MOAS** é uma plataforma em desenvolvimento para a gestão e monitoramento em tempo real de operações logísticas. O sistema foca em garantir a rastreabilidade total de cargas e descargas, documentando cada etapa com evidências fotográficas e métricas operacionais em tempo real.

Evolução do Projeto:
O projeto nasceu como uma ferramenta interna e passou por um processo de **profissionalização de arquitetura**, migrando de um gerenciamento de acesso estático para uma infraestrutura escalável.

Funcionalidades Principais
- **Registro de Operações:** Interface simplificada para operadores registrarem placas, motoristas, avarias e NFes.
- **Evidências Fotográficas:** Captura direta via câmera ou upload de galeria com armazenamento seguro.
- **Painel de Monitoramento (Real-time):** Visualização dinâmica do status das operações (Em andamento/Finalizado).
- **Gestão de Acessos (RBAC):** 
  - `Administrador`: Gestão total, edição e exclusão de registros.
  - `Operador`: Registro, finalização e pesquisa de operações.
  - `Comercial`: Acesso apenas para consulta e geração de relatórios.
- **Segurança Avançada:** Implementação de **Signed URLs** para proteção de mídias, garantindo que links de fotos expirem após 5 minutos.
- **Trilha de Auditoria:** Histórico visual de edições em registros finalizados.


Este é um projeto privado em fase de MVP.
