# Resolve TI - Ferramentas Técnicas Autônomas (Sem BD)

Sistema desenvolvido em **Next.js (App Router)** com **Tailwind CSS**, criado para permitir a emissão rápida, autônoma e profissional de:

1. **Ordem de Serviço (OS)**: Abertura de chamado técnico com campos abertos de identificação do cliente, dados detalhados do equipamento, senhas, checklist de estado físico, acessórios e defeito relatado.
2. **Orçamento Comercial**: Proposta de serviços e peças com adição dinâmica de itens, cálculo de subtotais e descontos em tempo real, formas de pagamento e geração automática de QR Code Pix.
3. **Certificado de Garantia**: Emissão do termo de entrega oficial com cláusulas contratuais em conformidade com o Código de Defesa do Consumidor (Art. 26).

---

## 🚀 Como Rodar o Projeto

```bash
# Instalar dependências (já instaladas)
npm install

# Iniciar servidor em modo desenvolvimento
npm run dev

# Gerar build de produção
npm run build

# Iniciar servidor de produção
npm start
```

O sistema estará acessível em: [http://localhost:3000](http://localhost:3000)

---

## 🌟 Principais Recursos

- **100% Autônomo (Zero Banco de Dados):** Não depende de Supabase nem de qualquer backend externo. Todos os campos são digitáveis livremente.
- **Persistência Local (LocalStorage):** Se você recarregar a página, seus últimos dados digitados continuam salvos no navegador.
- **Pré-visualização A4 e Impressão:** Cada ferramenta possui o espelho fiel da folha A4 com logo oficial e botão para gerar PDF ou imprimir via impressora térmica/jato de tinta.
- **Design System Fiel:** Mantém exatamente a identidade visual moderna, modo escuro (Dark Mode) e modo claro, menus com vidro fosco (glassmorphism) e tipografia Inter.
