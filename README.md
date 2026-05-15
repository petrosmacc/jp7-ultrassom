# JP7 Ultrassom — Diagnóstico de Composição Corporal e Sarcopenia

**Ferramenta clínica para avaliação de composição corporal por ultrassom modo‑A, baseada no protocolo de Jackson & Pollock (3 ou 7 dobras) e tabelas de referência segmentar.**

## 🔗 Acesso rápido
- **Aplicação online**: [https://seu-usuario.github.io/jp7-ultrassom/](https://seu-usuario.github.io/jp7-ultrassom/)
- **PWA**: pode ser instalada em celulares/desktops. Funciona offline.

## ⚙️ Funcionalidades
- Cálculo do percentual de gordura (%GC) a partir de 3 ou 7 medidas de gordura subcutânea (SAT, mm) usando as equações de Jackson & Pollock (1978/1980) e Siri (1961).
- **Correção específica para ultrassom**: fator automático de 0.95 (homens) / 0.97 (mulheres) aplicado à soma das dobras.
- Ajuste étnico para pessoas de pele negra (+2,95%, conforme Zillikens & Conway, 1990).
- Classificação global segundo as faixas do ACSM (Gordura Essencial, Atleta, Fitness, Aceitável, Sobrepeso, Obesidade), **contínuas e sem lacunas**.
- **Intervalo de confiança (SEE)** exibido no resultado: ±3.5% (homens) / ±3.8% (mulheres).
- Diagnóstico por segmento (todos os 7 sítios) com classificação: Atleta, Saudável, Transição, Alerta, Risco Metabólico.
- Avaliação de sarcopenia por 5 sítios musculares, com alertas visuais.
- **Validação de plausibilidade**: alertas para valores >50 mm ou diferenças extremas entre dobras.
- Três temas: Claro, Escuro, Sépia.
- Histórico das últimas 20 avaliações (armazenamento local).

## 🚀 Como usar
1. Acesse o link (ou abra o arquivo `index.html` localmente).
2. Escolha o tema desejado.
3. Preencha os dados do paciente (identificação opcional).
4. Insira as 7 espessuras de gordura subcutânea (SAT) ou apenas as 3 do protocolo reduzido.
5. Opcionalmente, insira as espessuras musculares (MT) para diagnóstico de sarcopenia.
6. Clique em **Calcular Diagnóstico Completo**.

## 📚 Fundamentação científica
- Jackson AS, Pollock ML. *Br J Nutr* 1978; **40**: 497‑504.
- Jackson AS, Pollock ML, Ward A. *Med Sci Sports Exerc* 1980; **12**: 175‑182.
- Siri WE. *Body composition from fluid spaces and density*. 1961.
- Zillikens MC, Conway JM. *Am J Clin Nutr* 1990; **52**: 45‑49.
- Fator de correção US: baseado em estudos comparativos entre ultrassom modo-A e plicômetro.

## 🛠 Tecnologia
Vanilla JS, HTML5, CSS3. Nenhuma dependência externa. PWA com Service Worker para uso offline.

## 📝 Licença
MIT
