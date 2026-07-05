# Derek Alvirde

<div align="center">

**Data Science Engineer** — Sistemas concurrentes · Métodos numéricos · Modelado matemático aplicado

Ciudad de México, México

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/derek-alvirde/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:derekjrex@gmail.com)

</div>

---

## Sobre mí

Ingeniería en Ciencia de Datos, con un origen poco convencional: técnico en Autotrónica antes de dedicarme al análisis de datos y al desarrollo de software. Esa base técnica define cómo trabajo — entiendo los sistemas desde sus componentes, no solo desde su interfaz.

Trabajo en la intersección entre matemáticas aplicadas, sistemas concurrentes y ciencia de datos: desde algoritmos de geometría computacional implementados con concurrencia real, hasta modelos de series de tiempo derivados de analogías con sistemas físicos (circuitos RLC). Freelance en análisis de datos, automatización y tutoría de programación desde 2024.

No busco la solución que "se ve bien" — busco la que resiste una re-derivación completa.

```python
class Derek:
    def __init__(self):
        self.role = "Data Science Engineer"
        self.background = "Autotrónica -> Ciencia de Datos"
        self.focus = ["Sistemas concurrentes", "Métodos numéricos",
                      "Modelado matemático", "Automatización"]
        self.principle = "Verificar cada resultado contra la fuente, no contra la intuición"

    def build(self, problem):
        return self.derive_from_first_principles(problem)

Derek().build("cualquier problema real")
```

---

## Stack técnico

**Lenguajes**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Concurrencia y sistemas**

![Multithreading](https://img.shields.io/badge/Concurrent%20Programming-FF6F00?style=for-the-badge)
![Swing](https://img.shields.io/badge/Java%20Swing-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Análisis y cómputo científico**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

**Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---

## Proyectos destacados

### SIGMA: Convex Protocol
> Juego de estrategia concurrente en Java, construido en equipo para un curso de Programación Concurrente

Motor de juego con tres hilos independientes sincronizados (juego, renderizado, entrada), implementando el **algoritmo de envolvente convexa de Chan** para la lógica central de territorio y control. El desarrollo real fue el reto: simetría de pausa/reanudación entre hilos, prevención de fugas de hilos, y detección de fin de juego sin condiciones de carrera.

**Stack:** `Java` `Concurrencia (ScheduledExecutorService, ScheduledFuture)` `Swing/EDT` `Algoritmos geométricos`

Presentado formalmente en semana de ingeniería, con documentación técnica y manual de usuario completos.

---

### Librería de Métodos Numéricos (pure Python)
> Librería propia, sin dependencias externas, construida desde cero

Implementación completa de los métodos numéricos fundamentales para ingeniería: integración (Trapecio, Simpson 1/3 y 3/8, Romberg, cuadratura Gaussiana), interpolación (Lagrange, diferencias divididas de Newton, Hermite), solución de EDOs (Euler, Heun, Taylor, RK4), y sistemas lineales iterativos (Jacobi, Gauss-Seidel con reordenamiento por dominancia diagonal).

**Stack:** `Python puro` — sin NumPy, sin SciPy. Cada método derivado y verificado a mano antes de codificarse.

---

### Análisis de sistemas LTI: analogía RLC ↔ AR(2)
> Proyecto integrador de modelado matemático aplicado a series de tiempo

Modelo que traduce el comportamiento dinámico de un circuito RLC a un modelo autorregresivo AR(2) mediante transformadas de Laplace, aplicado a pronóstico financiero. Puente entre teoría de sistemas físicos y modelado estadístico de series de tiempo.

**Stack:** `Transformadas de Laplace` `Modelos AR(2)` `Python` `Análisis de sistemas dinámicos`

---

### Basura Track
> Plan de negocio y diseño de sistema para rastreo inteligente de residuos

Sistema de rastreo de camiones de basura basado en GPS + IoT + IA, diseñado originalmente para CDMX y adaptado como plan de negocio para expansión internacional. Cubre desde la arquitectura del sistema hasta el análisis de viabilidad de mercado.

**Stack:** `GPS/IoT` `Arquitectura de sistemas` `Análisis de viabilidad`

---

### Eco-Balance
> Proyecto final de CS50x (HarvardX)

Aplicación web de monitoreo ambiental en tiempo real que calcula un Índice de Salud Ecológica (EHI) combinando métricas de biodiversidad, vegetación y contaminación, con dashboard interactivo y sistema de alertas.

**Stack:** `Flask` `Python` `Pandas` `HTML/CSS` `JavaScript`

---

## Principios de trabajo

- **Derivar, no memorizar.** Cada resultado —de un examen o de un modelo— se re-deriva desde principios base antes de aceptarse como válido.
- **Verificar contra la fuente.** La conveniencia nunca sustituye la corrección.
- **Construir en equipo, liderar cuando se necesita.** La experiencia técnica se pone al servicio del proyecto, no del ego.

---

## Actividad en GitHub

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=derekrex333&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" alt="Estadísticas de GitHub" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=derekrex333&layout=compact&theme=default&hide_border=true&langs_count=8" alt="Lenguajes más usados" height="165"/>
</p>
<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=derekrex333&theme=default&hide_border=true" alt="GitHub Streak"/>
</p>
<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=derekrex333&theme=github-light&hide_border=true" alt="Gráfico de actividad"/>
</p>

---

## Contacto

**Correo:** derekjrex@gmail.com
**Ubicación:** CDMX
**LinkedIn:** [derek-alvirde](https://www.linkedin.com/in/derek-alvirde/)

> El conocimiento cobra valor cuando se convierte en acción.
