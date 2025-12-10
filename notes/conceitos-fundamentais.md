# Conceitos Fundamentais
## Modelos de implementação

**Modelo On-premeses (local)** - ociosidade ou falta de recurso . Despesas fixas
**Modelo Cloud (nuvem)** - flexibilidade/ pague somente pelo uso. Despesas variáveis
**Modelo Hibrido** - on-premises e cloud

**Benefícios nuvem AWS**
- Economia de custo
- Foco no crescimento
- Elasticidade
- Economia de escala

---

### Região (Region) 
- É uma **área geográfica** contendo várias Availability Zones. 
- Cada região é projetada para ser isolada das outras regiões, garantindo resiliência e independência. 
- Contem 2 ou mais zonas de disponibilidade.  


### Zonas de Disponibilidade (Availability Zones - AZ) 
- Três ou mais data centers físicos independentes dentro de uma mesma região. 
- Objetivo da AZ é garantir **alta disponibilidade e ser tolerante a falhas**.
- Partes totalmente isoladas da infra global da AWS.

### Pontos de Presença (PoPs) (Edge Locations)
- Datacenter menores espalhados por locais no mundo.
- Para fazer a **distribuição de conteúdo (CDN)** com baixa latência e alta velocidade.
- Consumir mais próximo do cliente
  
 ---

## Modelo de Responsabilidade Compartilhada (Cliente vs AWS) 

### Cliente – NA Nuvem (aplicação) 
- Responsável pelo que é colocado na nuvem. 

### AWS – DA nuvem (fisicamente) 
- Responsável pela infraestrutura que executa a nuvem 

___

[⬅ Voltar ao índice](../README.md##estrutura)