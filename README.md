<div align="center">

# 🏗️ Evidencia: Arquitectura, Escala y Prácticas Reales

*No buscamos convencerte con aspiraciones; queremos hablar de ingeniero senior a ingeniero senior.*

<p>Aquí documentamos nuestras decisiones de diseño explícitas, métricas de resiliencia y cómo enfrentamos los datos duros de producción en el día a día.</p>

<br>

<img src="./02The%20Beauty%20of%20Boring%20Tech.gif" alt="The Beauty of Boring Tech" width="650" />

</div>

<br>

---

### 🛠️ Filosofía "Boring Technology" y Justificación de nuestro Stack

Nuestra elección tecnológica es una decisión deliberada y madura. En lugar de perseguir la herramienta de moda, priorizamos la **velocidad de entrega y la estabilidad** frente a una complejidad regulatoria y tributaria que cambia constantemente de forma simultánea en 5 países.

<div align="center">
  <img src="https://img.shields.io/badge/Ruby_on_Rails-CC0000?style=for-the-badge&logo=rubyonrails&logoColor=white" alt="Ruby on Rails" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</div>

<br>

<a href="https://drive.google.com/file/d/19sX57zgUO_pkUgP415fEGs_pyfN0Wt4v/view?usp=sharing" target="_blank">
  <img src="https://img.shields.io/badge/▶_Ver_Video-Por_qué_elegimos_Boring_Tech-0052CC?style=for-the-badge&logo=googledrive&logoColor=white" alt="Por qué elegimos Boring Tech" />
</a>

<br>

---

### 🧩 Arquitectura y Resiliencia en Escala (El Monolito)

¿Cómo absorbemos picos transaccionales masivos durante los cierres de nómina de fin de mes en **+2 millones de usuarios**?

A través de una **arquitectura híbrida** donde convive nuestro monolito robusto de Rails con microservicios dedicados a dominios específicos. En el frontend, utilizamos **monorepos con librerías de componentes centralizadas** para mantener un tipado estricto. Todo esto respaldado por una infraestructura **AWS Multi-Región** configurada para máxima alta disponibilidad.

<a href="https://drive.google.com/file/d/1sNOn8tAPKEXARGmDW0quZK3zYvmkLRgB/view?usp=drive_link" target="_blank">
  <img src="https://img.shields.io/badge/▶_Ver_Video-La_Arquitectura_y_el_Monolito_en_Buk-0052CC?style=for-the-badge&logo=googledrive&logoColor=white" alt="La arquitectura y el Monolito en Buk" />
</a>

<br>

---

### 🚢 Despliegues Estructurados y Cultura de Error

La responsabilidad de escalar rápido implica **fallar de forma segura**. Nuestra infraestructura está preparada para desacoplar los *releases* técnicos de los lanzamientos comerciales:

- ⚙️ **Integración Continua (CI/CD):** Agresiva y alta cobertura de pruebas automatizadas.
- 🚩 **Feature Flags:** Integrados como regla de diseño fundamental.
- 🤝 **Blameless Post-Mortems:** Cuando ocurren incidentes en producción, no buscamos culpables; hacemos análisis sistémico de causa raíz centrados únicamente en el aprendizaje del equipo.

---

### 👥 El Cliente en el Centro

> Como ingenieros en Buk, asumimos un contrato no escrito: entender ***qué, por qué y para quién*** construimos. 

Operamos sistemas de nómina y recursos humanos; sabemos que **cualquier falla en nuestro código impacta directamente en la liquidez financiera de miles de organizaciones y en los hogares de sus colaboradores**. Construimos con esa responsabilidad en mente todos los días.

<br>
<hr>

<div align="center">
  <h3>¿Listo para el siguiente paso?</h3>
  <p>Conoce nuestra comunidad, contribuciones Open Source y proceso de selección.</p>
  
  <a href="https://github.com/CLeonRecruiter/Conversion-y-Comunidad-Buker/blob/main/README.md">
    <img src="https://img.shields.io/badge/Siguiente_paso-Pilar_3:_Conversión_y_Comunidad-1A1A1A?style=for-the-badge&logo=github&logoColor=white" alt="Explora nuestro Pilar 3" />
  </a>
</div>
