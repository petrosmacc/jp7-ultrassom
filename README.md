# JP7 Ultrassom — Diagnóstico de Composição Corporal e Sarcopenia

**Ferramenta clínica para avaliação de composição corporal por ultrassom modo‑A, baseada no protocolo de Jackson & Pollock (7 dobras) e tabelas de referência segmentar.**

## 🔗 Acesso rápido
- **Aplicação online**: [https://seu-usuario.github.io/jp7-ultrassom/](https://seu-usuario.github.io/jp7-ultrassom/)
- **PWA**: pode ser instalada em celulares/desktops. Funciona offline.

## ⚙️ Funcionalidades
- Cálculo do percentual de gordura (%GC) a partir de 7 medidas de gordura subcutânea (SAT, mm) usando as equações de Jackson & Pollock (1978/1980) e Siri (1961).
- Ajuste étnico para pessoas de pele negra (+2,95%, conforme Zillikens & Conway, 1990).
- Classificação global segundo as faixas do ACSM (Gordura Essencial, Atleta, Fitness, Aceitável, Sobrepeso, Obesidade), **contínuas e sem lacunas**.
- Diagnóstico por segmento (Tríceps, Subescapular, Abdominal, Suprailíaca, Coxa Anterior) com classificação: Atleta, Saudável, Transição, Alerta, Risco Metabólico.
- Avaliação de sarcopenia por 5 sítios musculares (Bíceps, Quadríceps, Reto Femoral, Reto Abdominal, Tibial Anterior), com alertas visuais.
- Três temas: Claro, Escuro, Sépia.
- Histórico das últimas 20 avaliações (armazenamento local).

## 🚀 Como usar
1. Acesse o link (ou abra o arquivo `index.html` localmente).
2. Escolha o tema desejado.
3. Preencha os dados do paciente (identificação opcional).
4. Insira as 7 espessuras de gordura subcutânea (SAT) em milímetros.
5. Opcionalmente, insira as espessuras musculares (MT) para diagnóstico de sarcopenia.
6. Clique em **Calcular Diagnóstico Completo**.

## 🧪 Testes de referência
| Caso | Sexo | SAT (mm) | %GC esperado (Siri) | Classificação ACSM |
|------|------|----------|----------------------|---------------------|
| Mulher fitness (branca) | F | 55.5 | ~13.1% | Gordura Essencial |
| Homem atleta (negro) | M | 26.0 | ~8.8%* | Atleta |

*Com ajuste étnico (5.8% bruto + 2.95%).

## 📚 Fundamentação científica
- Jackson AS, Pollock ML. *Br J Nutr* 1978; **40**: 497‑504.
- Jackson AS, Pollock ML, Ward A. *Med Sci Sports Exerc* 1980; **12**: 175‑182.
- Siri WE. *Body composition from fluid spaces and density*. 1961.
- Zillikens MC, Conway JM. *Am J Clin Nutr* 1990; **52**: 45‑49.

## 🛠 Tecnologia
Vanilla JS, HTML5, CSS3. Nenhuma dependência externa. PWA com Service Worker para uso offline.

## 📝 Licença
MIT
