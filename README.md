# Plan Integral 12 Semanas · José · Machachi Ecuador (3.000 m)

> PWA instalable · Todo en un solo archivo HTML offline · Diseñado para móvil y escritorio

## 📋 Diagnóstico

Paciente masculino, 47 años (nacido 22/05/1979), residente en Machachi (provincia de Pichincha, Ecuador) a 3.000 msnm:

- **HPB grado II sintomática** — próstata 60 g, residuo vesical 259 ml (severo)
- **PSA 3,67 ng/mL** — elevado para la edad (densidad PSA 0,061 sugiere benignidad)
- **HbA1c 6,2% + ayuno 114 mg/dL + HOMA-IR 2,77** — debut Diabetes Tipo 2
- **Dislipidemia aterogénica** — CT 251, LDL 153,6, TG 201, HDL 57,2
- **IMC 27,7** — sobrepeso grado I (83 kg / 1,73 m)
- **Adaptación a altitud** — Hb 17,7 y Hcto 52,7% esperables para 3.000 m

## 🎯 Objetivos 12 semanas

| Indicador | Inicial | Meta |
|---|---|---|
| Peso | 83 kg | 76 – 78 kg |
| HbA1c | 6,2% | < 5,7% (remisión) |
| LDL | 153,6 mg/dL | < 100 mg/dL |
| TG | 201 mg/dL | < 150 mg/dL |
| Sueño | 6 h | ≥ 7 h |
| Pasos/día | — | ≥ 8.000 |
| Residuo vesical | 259 ml | < 100 ml (con tto urológico) |

## 🚀 Cómo usar

### Opción 1 — Abrir directamente
1. Abre `index.html` en cualquier navegador (Chrome, Safari, Firefox, Edge).
2. Listo. Funciona 100% offline después de la primera carga.

### Opción 2 — Instalar como PWA (móvil)
1. Sube el repo a GitHub Pages, Netlify o Vercel.
2. Abre la URL en Chrome iOS/Android → "Añadir a pantalla de inicio".
3. Funciona offline, con icono propio.

### Opción 3 — Servir local
```bash
python3 -m http.server 8000
# luego: http://localhost:8000
```

## 🗂️ Secciones del plan

| # | Pestaña | Contenido |
|---|---|---|
| 1 | **Perfil Clínico** | Diagnóstico integral, indicadores basales, metas, plan farmacológico esperado |
| 2 | **Nutrición** | Distribución de macronutrientes, estructura diaria, hidratación, lista permitida/prohibida, superalimentos andinos |
| 3 | **Menú Semanal** | 7 días completos con kcal/porción, adaptado a Machachi (quinua, trucha, cuy, chocho, mortiño) |
| 4 | **Compras** | Lista semanal con costos y dónde comprar (Mercado Machachi, Supermaxi Sangolquí, etc.) |
| 5 | **Entrenamiento** | Plan 12 semanas en 3 fases con zonas FC ajustadas a 3.000 m, FCmax 163 lpm |
| 6 | **Progreso** | Tracker semanal (peso, cintura, glucosa, PA, pasos) con almacenamiento local |
| 7 | **Suplementos** | Vit D3, Omega-3, Mg, Cr, Berberina, Canela, Saw Palmetto + costos y evidencias |
| 8 | **Alarmas** | Signos de urgencia urológica, metabólica y de altitud; contactos Machachi/Sangolquí |

## 📐 Cálculo calórico

- **Tasa Metabólica Basal** (Mifflin-St Jeor): 1.714 kcal/día
- **GET** (factor 1,4 por actividad laboral): ~2.400 kcal/día
- **Déficit objetivo**: −500 kcal/día → **1.900 kcal/día**
- **Macros**: 25% proteína · 35% grasas · 35% carbohidratos · ≥35 g fibra

## 🏔️ Ajustes para altitud (3.000 m)

- FCmax ajustada: 220 − 47 − 10 = **163 lpm**
- VO₂max 15–20% menor que a nivel del mar → intensidades más bajas
- Hidratación crítica: ≥ 3 L/día
- Vitamina D3: suplementar 4.000 UI/día (la resistencia insulínica la depleta)
- Evitar entrenar 11:00–15:00 (radiación UV extrema)

## ⚠️ Disclaimer médico

> Este plan es COMPLEMENTARIO al tratamiento farmacológico que defina tu médico internista y urólogo. NO suspendas ni inicies medicación por tu cuenta. **Toda la información aquí presente es educativa y no sustituye el criterio clínico profesional.**

## 📂 Estructura del repo

```
.
├── index.html       # App completa (PWA single-file, ~64 KB)
├── manifest.json    # PWA manifest
├── icon-192.png     # Ícono 192×192
├── icon-512.png     # Ícono 512×512
└── README.md        # Este archivo
```

## 📅 Calendario de controles médicos

| Semana | Acción |
|---|---|
| Sem 0 | Cita internista + cita urólogo |
| Sem 1 | Solicitar PSA libre, urocultivo, HbA1c confirmatoria |
| Sem 4 | Control métricas (peso, cintura, PA) |
| Sem 8 | Control metabólico intermedio |
| Sem 12 | **Laboratorio completo post-plan** (HbA1c, glucosa, perfil lipídico, creatinina, PSA) |

## 📜 Licencia

Uso personal. Para redistribuir, conserva atribución.

