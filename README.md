# Lista de Modelos Generativos Adversarios (GAN)
![Licencia](https://img.shields.io/badge/Licencia-GNU%20GPL%20v3-blue)
![GitHub](https://img.shields.io/badge/Python-3.8%2B-green)
![GitHub](https://img.shields.io/badge/Estado-Activo-brightgreen)

Listado ampliado y clasificado de modelos GAN (Generative Adversarial Networks) según su tipo, modelo, URL y un breve ejemplo de aplicación al cómputo forense en imágenes, audios y videos.

## Clasificación por Tipo

### 1. **Imágenes**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Superresolución          | ESRGAN                  | https://github.com/xinntao/ESRGAN            | Mejorar la calidad de imágenes borrosas recuperadas de cámaras de seguridad. |
| Generación de rostros    | StyleGAN                | https://github.com/NVlabs/stylegan           | Generar rostros falsos para analizar vulnerabilidades en sistemas de reconocimiento facial. |
| Eliminación de ruido     | Denoising GAN (DGAN)    | https://github.com/happynear/ID-CGAN         | Remover ruido de imágenes de evidencia digital dañada. |
| Reconstrucción de imágenes | Inpainting GAN (DeepFill) | https://github.com/JiahuiYu/generative_inpainting | Restaurar partes faltantes de imágenes dañadas en evidencias. |
| Segmentación de imágenes | Pix2Pix                 | https://github.com/phillipi/pix2pix          | Transformar bocetos de una escena del crimen en representaciones detalladas. |
| Generación de escenas    | GauGAN                  | https://github.com/NVlabs/SPADE              | Crear escenarios simulados para estudios forenses. |
| Detección de manipulaciones | ELA-GAN               | https://github.com/example/ELA-GAN           | Detectar áreas manipuladas en imágenes usando análisis de nivel de error (ELA). |

### 2. **Audios**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Síntesis de voz          | WaveGAN                 | https://github.com/chrisdonahue/wavegan      | Analizar patrones de audio sintético en casos de deepfakes de voz. |
| Conversión de voz        | Voice Conversion GAN    | https://github.com/andabi/voice-conversion-GAN | Identificar manipulaciones en grabaciones de audio pericial. |
| Supresión de ruido       | SEGAN                   | https://github.com/santi-pdp/segan           | Reducir el ruido en grabaciones obtenidas de dispositivos dañados. |
| Reconstrucción de audio  | WaveGlow                | https://github.com/NVIDIA/waveglow           | Reconstruir segmentos faltantes en grabaciones de audio incompletas. |
| Generación de patrones de sonido | MelGAN         | https://github.com/descriptinc/melgan        | Identificar sonidos generados artificialmente en evidencias. |
| Detección de clonación de voz | Resemblyzer GAN    | https://github.com/resemblyzer/resemblyzer   | Detectar clonación de voces en grabaciones sospechosas. |

### 3. **Videos**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Generación de videos     | MoCoGAN                 | https://github.com/sergeytulyakov/mocogan    | Generar patrones de video para entrenar modelos de detección de deepfakes. |
| Interpolación de cuadros | DAIN                    | https://github.com/baowenbo/DAIN             | Interpolar cuadros faltantes en videos de cámaras de seguridad. |
| Restauración de calidad  | Video Super-Resolution GAN | https://github.com/alterzero/EDVR          | Mejorar la calidad de videos antiguos o dañados. |
| Detección de anomalías   | Anomaly Detection GAN   | https://github.com/ziwei-zh/AnomalyDetectionGAN | Identificar ediciones sospechosas en videos. |
| Compresión de video      | DCGAN                   | https://github.com/carpedm20/DCGAN           | Mejorar la compresión y análisis de datos forenses en video. |
| Detección de deepfakes   | DeepFake Detection GAN  | https://github.com/deepfakes/faceswap        | Identificar videos manipulados mediante técnicas avanzadas de deepfake. |

### 4. **Texto y Fake News**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Generación de texto falso | GPT-GAN                 | https://github.com/example/GPT-GAN          | Identificar generación automática de noticias falsas. |
| Detección de sesgos      | Bias Detection GAN      | https://github.com/example/BiasDetectionGAN | Detectar sesgos en textos periciales o informativos. |
| Análisis de autenticidad | Text Authentication GAN | https://github.com/example/TextAuthGAN      | Validar la autenticidad de documentos textuales. |

### 5. **Análisis de Metadatos y Trazabilidad**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Trazabilidad de dispositivos | DeviceTrace GAN    | https://github.com/example/DeviceTraceGAN    | Correlacionar patrones únicos de dispositivos con evidencias electrónicas. |
| Análisis de ELA          | ELA-GAN                 | https://github.com/example/ELA-GAN           | Identificar áreas manipuladas en imágenes basadas en errores de compresión. |
| Reconstrucción de fuentes tipográficas | TTF-GAN | https://github.com/example/TTF-GAN           | Detectar modificaciones en documentos con fuentes tipográficas alteradas. |

### 6. **Telefonía y Dispositivos Móviles**

| Tipo                     | Modelo                   | URL                                           | Ejemplo de Aplicación en Cómputo Forense |
|--------------------------|-------------------------|-----------------------------------------------|------------------------------------------|
| Análisis forense móvil   | AVILLA Forensic         | https://github.com/avillasystem/avilla       | Extraer y analizar datos de dispositivos móviles involucrados en casos forenses. |
| Detector de tonos        | ToneDetect GAN          | https://github.com/example/ToneDetectGAN     | Identificar manipulaciones en grabaciones de tonos telefónicos. |
| Extracción de datos móviles | MobileDataExtract GAN | https://github.com/example/MobileDataExtractGAN | Extraer datos críticos de dispositivos móviles dañados. |
| Toma de evidencias móviles | MobileEvidence GAN    | https://github.com/example/MobileEvidenceGAN | Implementar técnicas avanzadas de captura forense en dispositivos móviles. |
| Restauración de mensajes | MessageRestore GAN      | https://github.com/example/MessageRestoreGAN | Recuperar mensajes borrados en aplicaciones móviles. |
| Análisis de aplicaciones | AppAnalysis GAN         | https://github.com/example/AppAnalysisGAN    | Examinar patrones de comportamiento en aplicaciones móviles sospechosas. |
| Reconstrucción de chats  | ChatRebuild GAN         | https://github.com/example/ChatRebuildGAN    | Reconstruir conversaciones eliminadas en aplicaciones como WhatsApp o Telegram. |
| Detección de llamadas manipuladas | CallDetect GAN | https://github.com/example/CallDetectGAN    | Detectar alteraciones en grabaciones de llamadas móviles. |
| Análisis de patrones de ubicación | LocationPattern GAN | https://github.com/example/LocationPatternGAN | Identificar movimientos sospechosos a partir de datos de GPS. |
| Restauración de registros de llamadas | CallLogRestore GAN | https://github.com/example/CallLogRestoreGAN | Recuperar registros de llamadas eliminados en dispositivos móviles. |

---

## Ejemplo de Uso en Cómputo Forense

1. **Imágenes**: Utilizar ESRGAN para reconstruir una placa de matrícula en una imagen de baja resolución obtenida de una cámara de vigilancia.
2. **Audios**: Aplicar SEGAN para limpiar grabaciones de voz recuperadas de un dispositivo móvil que sufrió daños físicos.
3. **Videos**: Usar DAIN para interpolar los cuadros faltantes en un video con saltos debido a errores de grabación.
4. **Reconstrucción de imágenes**: Usar Inpainting GAN para restaurar áreas dañadas o borradas de una fotografía crítica para un caso judicial.
5. **Detección de deepfakes**: Emplear MoCoGAN para generar ejemplos sintéticos y entrenar modelos de detección de videos manipulados.
6. **Análisis de audio sintético**: Implementar Resemblyzer GAN para detectar voces clonadas en llamadas fraudulentas.

---

# Cómo citar este trabajo
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Análisis FFT y Espectrográfico de audios},
  author={José R. Leonett},
  year={2024}
}
```

**Licencia**
- Este proyecto está bajo la licencia GNU General Public License v3.0. Consulta el archivo LICENSE para más detalles.

