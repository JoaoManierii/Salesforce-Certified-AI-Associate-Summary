```markdown
# Ethical Considerations of AI 🚀  
**Exam Weight: 39%**

---

## Meet Salesforce’s Trusted AI Principles

![Trusted AI Principles](image.png)

Em 2018, articulamos nossos **Trusted AI Principles** específicos para produtos, casos de uso e clientes da Salesforce. Após um ano de feedback de diversas equipes e aprovação da alta liderança, definimos cinco princípios fundamentais:

1. **Responsible**  
   — Protegemos direitos humanos, privacidade e seguimos padrões científicos rigorosos.  
   — Clientes devem usar IA em conformidade com nossa Acceptable Use Policy.

2. **Accountable**  
   — Prestamos contas a clientes, parceiros e sociedade.  
   — Recebemos feedback independente e mitigamos riscos continuamente.

3. **Transparent**  
   — Explicamos o “porquê” de cada recomendação ou previsão.  
   — Publicamos model cards e oferecemos explainability on-demand.

4. **Empowering**  
   — IA como complemento à capacidade humana: clicks, not code.  
   — Educação grátis via Trailhead e in-app guidance para uso responsável.

5. **Inclusive**  
   — Testamos modelos em datasets diversos e representativos.  
   — Promovemos diversidade em equipes e contextos de uso.

### From Principles to Practice

#### Responsible  
- Avaliamos “can we?” **e** “should we?” antes de lançar features.  
- Colaboramos com human rights experts e criamos ferramentas para detectar e mitigar bias (e.g., flagging protected attributes).  
- Segregamos, criptografamos e pseudonimizamos dados sensíveis; seguimos leis e padrões de qualidade.

#### Accountable  
- Mantemos Ethical Use Advisory Council e Customer Advisory Boards.  
- Participamos de grupos do setor (NIST, AI Advisory Committees, etc.).  
- Canais internos (Slack, corporate reporting) para reportar preocupações.

#### Transparent  
- Publicamos **Model Cards** com detalhes de criação, uso e performance.  
- Garantimos que clientes controlem seus dados e modelos em todos os momentos.

#### Empowering  
- Construímos apps de IA sem código (“clicks not code”).  
- Oferecemos Trailhead gratuito e ferramentas (disparate impact checks, auto model cards).  
- Pesquisa de ponta para manter clientes na vanguarda.

#### Inclusive  
- Workshops de Consequence Scanning e Build with Intention.  
- Equipes diversas para refletir múltiplas perspectivas.  
- Testes com dados representativos para evitar viés.

---

## Generative AI: 5 Guidelines for Responsible Development

### Generative AI at Salesforce  
- Integrada ao Einstein 1: ~200 bilhões de previsões diárias.  
- Aplicações em Sales, Service, Marketing, Commerce e IT.  
- Exploramos AI-generated code para devs e não-devs.

### Guidelines for Trusted Generative AI

1. **Accuracy**  
   – Enable customers to train on their own data.  
   – Cite sources, chain-of-thought explainability, highlight uncertainties.

2. **Safety**  
   – Bias, toxicity & robustness assessments; red teaming.  
   – PII protection; enforce sandbox publishing for code.

3. **Honesty**  
   – Respect data provenance & consent.  
   – Disclose AI-generated content (watermarks, labels).

4. **Empowerment**  
   – Balance full automation vs. human judgment.  
   – Generate ALT text; supercharge human workflows.

5. **Sustainability**  
   – Develop right-sized models to reduce carbon footprint.  
   – Smaller, well-trained models may outperform gigantes.

---

## AI Ethics Maturity Model

| Principle    | Practices                                                                 |
|--------------|----------------------------------------------------------------------------|
| Responsible  | Human rights experts; bias mitigation tools; open research                 |
| Accountable  | Customer feedback loops; Ethics Council; external reviews                 |
| Transparent  | Model explainability; customer data control; clear terms                  |
| Empowering   | Clicks-not-code apps; free AI education (Trailhead); research breakthroughs|
| Inclusive    | Diverse datasets; Consequence Scanning; inclusive team building           |

---

## Ethical Use of Technology in Salesforce

Salesforce publica nossos **Responsible Marketing Principles** e recomendações para personalização ética:

- **Transparência de Segurança**: Documentos públicos (SOC, ISO, PCI, C5, Cyber Essentials, TRUSTe).  
- **Consentimento & Transparência**: Informe dados coletados, finalidades e ofereça opt-out claro.  
- **Benefício em troca de dados**: Valor tangível para o cliente — conteúdo relevante, ofertas personalizadas.  
- **Intenção > Demografia**: Segmente por comportamento/interesse, não apenas atributos demográficos.  
- **Limitação de Frequência**: Defina throttling e message caps para evitar sobrecarga.

### Cenários de Mensagens Comportamentais

1. **Abandon Cart**: lembrete oportuno para concluir compra.  
2. **Abandon Browse**: cupom com explicação “vimos que você olhou X”.  
3. **Price Drop**: alerta de desconto + opção de feedback “já comprei / não me interessa”.  
4. **Novidades na Categoria Favorita**: “lançamos Y, achamos que você vai amar”.  
5. **Pós-compra**: instruções de uso, apps para tracking, cross-sell.  
6. **Real-Time Triggers**: eventos em tempo real (BOPIS, checkout) para experiência fluida.

---

## Learn Privacy and Data Protection Law (GDPR)

### Background & Scope  
– Direito fundamental à privacidade na UE desde 1995.  
– GDPR em vigor em 25 May 2018, harmonizando regras e aumentando multas (até €20 M ou 4% da receita).

### Key Terms

| Term                   | Definition                                                                       |
|------------------------|----------------------------------------------------------------------------------|
| **Data Subject**       | Pessoa natural identificada/identificável                                        |
| **Personal Data**      | Qualquer informação relacionada a uma pessoa                                    |
| **Sensitive Data**     | Origem étnica, opiniões políticas, saúde, biometria, etc.                        |
| **Processing**         | Qualquer operação com dados (coletar, armazenar, compartilhar…)                  |
| **Controller**         | Define finalidades e meios de processamento                                     |
| **Processor**          | Processa dados em nome do Controller                                            |
| **Pseudonymous Data**  | Reversível apenas com informação adicional separada e protegida                  |
| **Anonymous Data**     | Irreversível, não constitui personal data                                       |

### Major Changes

- **Legal Bases**: consentimento livre, específico e demonstrável, ou outras bases (contrato, obrigação legal).  
- **Processor Obligations**: contratos, segurança, compliance.  
- **Breach Notification**: até 72 h para DPA; titulares notificados se high risk.  
- **DPO Requirement**: para processamento em larga escala de dados sensíveis.  
- **Fines**: até €20 M ou 4% da receita global.  
- **Cross-Border Transfers**: BCRs, Standard Contractual Clauses, Codes of Conduct.  
- **Profiling Restrictions**: decisões automatizadas de alto impacto só com salvaguardas.  
- **Data Subject Rights**: access, rectification, erase (“right to be forgotten”), portability, objection.

### GDPR Principles

1. **Lawfulness, Fairness & Transparency** – aviso claro em coleta e uso.  
2. **Purpose Limitation** – dados usados só para fins explícitos.  
3. **Data Minimization** – coletar apenas o necessário.  
4. **Accuracy** – manter dados atualizados.  
5. **Storage Limitation** – reter só o tempo necessário.  
6. **Integrity & Confidentiality** – medidas técnicas e organizacionais (encryption, pseudonymization).  
7. **Accountability** – controller demonstra compliance, mantém registros e DPIAs.

### Implementation Steps

1. **Leadership Buy-in** & cross-functional team (IT, Legal, HR, Marketing).  
2. **Data Inventory & Mapping**: identificar fontes, tipos, fluxos.  
3. **Gap Analysis & Risk Assessment**: DPIAs para high-risk processing.  
4. **Policies & Processes**: privacy notices, consent management, processor contracts, incident response.  
5. **Training & Awareness**: para funcionários e fornecedores.  
6. **Ongoing Monitoring & Audits**: revisões periódicas e atualização de controles.  
7. **Documentation**: privacy notices, records of processing, DPIAs, BCRs/SCCs, DPO appointment.

### Salesforce’s Support

- **Data Processing Addendum** com SCCs e BCRs aprovadas pela UE.  
- **Trust & Compliance Documentation** para cada serviço (ISO 27001/18, SOC, PCI, C5, Cyber Essentials, TRUSTe).  
- **Customer Control**: dados pertencem ao cliente; configurações de privacidade by default and by design.

