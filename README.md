### Hola, soy Martín 👋

Developer autodidacta especializado en **Python y Machine Learning**. Llevo 5
años formándome por mi cuenta — desde fundamentos de programación hasta
entrenamiento y validación de modelos de deep learning sobre datos clínicos
reales, entrenamiento de modelos de IA, optimizacion y automatizacion de procesos.

No vengo de un rol de desarrollo formal todavía, pero mis proyectos son
sistemas completos de punta a punta: pipelines de ML entrenados y validados,
apps desplegadas y accesibles online resolviendo problemas de negocio reales,
y decisiones técnicas documentadas y justificadas, no solo código que
funciona.

#### Stack técnico
- **Lenguaje:** Python
- **ML / Deep Learning:** PyTorch, MONAI, nnU-Net, LightGBM, scikit-learn
- **Imagen médica:** SimpleITK, pydicom, highdicom, DICOM SEG/SR
- **Backend:** Flask, FastAPI
- **Datos / RAG:** ChromaDB, embeddings, Ollama
- **Optimización:** Google OR-Tools (CP-SAT)
- **Infraestructura:** despliegue self-hosted (homelab), Cloudflare Tunnel
- **Testing:** pytest

#### Proyectos destacados

**[picai-cspca-DICOM-pipeline](https://github.com/marrtincho/picai-cspca-DICOM-pipeline)**
— pipeline de deep learning 3D en cascada (nnU-Net + MedicalNet + LightGBM)
para detección, localización y gradación de cáncer de próstata clínicamente
significativo sobre mpMRI, validado sobre DICOM clínico real con salida
DICOM SEG/SR compatible con PACS. Incluye métricas reportadas honestamente,
limitaciones explícitas y razonamiento de diseño documentado.

**[reception-assistant-rag](https://github.com/marrtincho/reception-assistant-rag)**
— asistente RAG de uso interno para el equipo de recepción de un hotel,
con modelos locales vía Ollama. Responde dudas operativas a partir de la
documentación del hotel sin entrenar ni ajustar ningún modelo. Sistema
completo de punta a punta (221 tests): ingesta, embeddings/indexado,
retrieval, generación e interfaz Streamlit, con caché semántico de
respuestas validadas y una pestaña de métricas con diagnóstico operativo
automático. Decisiones técnicas documentadas en `docs/decisiones/`.

**[hotel-revenue-forecast](https://github.com/marrtincho/hotel-revenue-forecast)**
— previsión de ocupación por tipo de habitación a 30/60/90 días mediante
pickup forecasting y gradient boosting. Validación temporal estricta,
comparación obligatoria contra baselines de negocio, restricciones monótonas
para forzar coherencia con la lógica del dominio, e interfaz para usuarios no
técnicos. Documenta dos bugs reales de producción —un modelo sobreajustado que
había dejado de responder a la demanda actual, y lógica de entrenamiento
duplicada que se desincronizó— junto al método que los detectó.

**[hotel-shift-scheduler-cpsat](https://github.com/marrtincho/hotel-shift-scheduler-cpsat)**
— sistema de optimización de turnos de recepción con Google OR-Tools
(CP-SAT), desplegado y en uso online desde mi propio homelab
([demo en vivo](https://horarios.lobbysoftware.dpdns.org/)). Actualmente en
fase de ajuste antes de su adopción formal y definitiva.

#### Contacto
- Email: mropero21@gmail.com
- LinkedIn: [linkedin.com/in/martin-ropero](https://linkedin.com/in/martin-ropero/)
