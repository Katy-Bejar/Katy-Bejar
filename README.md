\documentclass[10.5pt,a4paper]{article}
% CV adaptado a Dominix - Desarrolladora Junior, formato ATS, dos páginas.
\usepackage[a4paper,left=1.65cm,right=1.65cm,top=1.35cm,bottom=1.32cm]{geometry}
\usepackage{fontspec}
\setmainfont{Carlito}
\usepackage[spanish,es-noquoting]{babel}
\usepackage{hyperref}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{xcolor}
\usepackage{microtype}
\hypersetup{colorlinks=true,urlcolor=black,linkcolor=black,pdfauthor={Katherine Nikole Béjar Román},pdftitle={CV Katherine Béjar - Desarrolladora Full Stack Junior - Dominix}}
\definecolor{ink}{HTML}{193044}
\definecolor{muted}{HTML}{465E6D}
\definecolor{rule}{HTML}{A7C1D2}
\color{ink}
\pagestyle{empty}
\setlength{\parindent}{0pt}
\setlength{\parskip}{2pt}
\setlength{\emergencystretch}{2.5em}
\setlist[itemize]{leftmargin=1.35em,topsep=2pt,itemsep=1.5pt,parsep=0pt,partopsep=0pt}
\titleformat{\section}{\bfseries\fontsize{11.1}{13}\selectfont\color{ink}}{}{0pt}{}[\color{rule}\titlerule]
\titlespacing*{\section}{0pt}{8pt}{4pt}
\newcommand{\role}[3]{%
\textbf{#1}\hfill\textbf{#2}\\[-2pt]
{\color{muted}\itshape #3}\par\vspace{-4pt}}
\newcommand{\project}[3]{\textbf{#1}\hfill{\color{muted}\textbf{#2}}\\[-1pt]{\color{muted}\itshape #3}\par\vspace{-4pt}}
\begin{document}
\begin{center}
{\fontsize{19}{21}\selectfont\bfseries Katherine Nikole Béjar Román}\\[3pt]
{\fontsize{11.7}{13.4}\selectfont\bfseries Desarrolladora Full Stack Junior | React, Laravel, Node.js y SQL}\\[4pt]
Arequipa, Perú \quad|\quad +51 944 818 827 \quad|\quad \href{mailto:kbejarr@gmail.com}{kbejarr@gmail.com}\\[2pt]
\href{https://www.linkedin.com/in/katherine-nikole-bejar-roman/}{linkedin.com/in/katherine-nikole-bejar-roman}\quad|\quad \href{https://github.com/Katy-Bejar}{github.com/Katy-Bejar}
\end{center}
\vspace{-10pt}

\section{Perfil profesional}
Bachiller en Ciencia de la Computación por la Universidad Nacional de San Agustín de Arequipa, con experiencia en \textbf{desarrollo full stack, aplicaciones web responsivas, APIs REST e integración de bases de datos}. He trabajado con \textbf{PHP/Laravel, React/Next.js y Node.js} en sistemas internos, intranets y sitios web, además de Python/FastAPI, MySQL y AWS en plataformas empresariales. Manejo \textbf{SQL, PostgreSQL y Tailwind CSS} como parte de mis competencias técnicas. También he participado en integraciones, automatizaciones y soluciones con \textbf{agentes de IA y modelos de lenguaje (LLM)}. Busco aportar al desarrollo de soluciones web mantenibles, colaborando en todo el ciclo de construcción y mejora del software.

\section{Tecnologías y competencias}
\textbf{Frontend:} JavaScript, TypeScript, React.js, Next.js, Tailwind CSS, HTML5, CSS3, diseño responsivo.\\
\textbf{Backend:} PHP, Laravel, Node.js, Express.js, Python, FastAPI, APIs REST, JSON, webhooks e integración entre servicios.\\
\textbf{Bases de datos:} PostgreSQL, MySQL, SQL, SQLite, Supabase, AWS RDS; consultas, validación y persistencia de datos.\\
\textbf{Herramientas y despliegue:} Git, GitHub, GitHub Actions, Docker, AWS (EC2, RDS, S3), Vercel y CI/CD.\\
\textbf{IA y automatización:} Mastra, DeepSeek (LLM), agentes conversacionales, IBM Watson Assistant, Meta WhatsApp Business y Kapso; pruebas funcionales y de integración.

\section{Experiencia profesional}
\role{Desarrolladora Full Stack / Backend --- TIC CORP S.A.C.}{Mar 2026 -- Nov 2026}{Python, FastAPI, Node.js, MySQL, AWS, Mastra, DeepSeek \quad|\quad Arequipa, Perú}
\begin{itemize}
  \item Desarrollé e integré \textbf{servicios backend y APIs REST} para una plataforma empresarial multiempresa, con validaciones, consultas SQL y persistencia de información en \textbf{MySQL sobre AWS RDS}.
  \item Participé en el desarrollo de un motor de \textbf{alertas accionables y automatizaciones}, conectando datos del ERP, eventos, notificaciones y acciones de usuarios entre distintos servicios.
  \item Colaboré en \textbf{ALBA}, un agente de IA integrado con WhatsApp (Meta y Kapso), y en workflows con \textbf{Mastra y DeepSeek (LLM)}, utilizando webhooks, formularios y APIs REST.
  \item Realicé pruebas funcionales y de integración, investigué incidencias y validé controles contra operaciones duplicadas; apoyé despliegues con \textbf{Docker, GitHub Actions y AWS EC2}.
\end{itemize}

\role{Desarrolladora Full Stack --- Neon House LED S.A.C.}{Mar 2025 -- Jun 2025}{PHP, Laravel, React, Next.js, MySQL \quad|\quad Arequipa, Perú}
\begin{itemize}
  \item \textbf{Migré funcionalidades de un sistema interno de PHP a Laravel}, mejorando la organización del backend y facilitando su mantenimiento.
  \item Desarrollé y adapté \textbf{interfaces web responsivas con React y Next.js} durante la modernización de la intranet corporativa.
  \item Integré componentes del frontend, lógica del backend y consultas a \textbf{MySQL} durante la transición tecnológica.
\end{itemize}

\role{Desarrolladora Full Stack --- Auro Laboratorio e Ingeniería S.A.C.}{Feb 2025 -- May 2025}{React, Next.js, Node.js, MySQL \quad|\quad Arequipa, Perú}
\begin{itemize}
  \item Desarrollé un \textbf{sitio web institucional responsivo con React y Next.js}, mejorando la navegación y la experiencia en dispositivos móviles.
  \item Integré funcionalidades dinámicas con \textbf{Node.js y MySQL} para gestionar y presentar información del sitio.
\end{itemize}

\newpage
\section{Proyectos destacados}
\project{Plataforma web gamificada para comunidad musical}{2026}{Next.js, React, Supabase, Tailwind CSS, Vercel, PWA}
\begin{itemize}
  \item Desarrollé una \textbf{aplicación web con React y Next.js} con modos de juego, rankings, recompensas y seguimiento del progreso de usuarios, utilizando \textbf{Tailwind CSS} para la interfaz.
  \item Integré autenticación, gestión de usuarios y almacenamiento de datos con \textbf{Supabase}; desplegué la aplicación en \textbf{Vercel} y adapté su experiencia móvil como \textbf{PWA}.
\end{itemize}

\project{EasyProcess --- Plataforma interactiva con chatbot}{2022}{Python, Flask, SQLite, HTML, CSS, IBM Watson Assistant}
\begin{itemize}
  \item Desarrollé una aplicación web para consultas estudiantiles, combinando interfaz, backend en \textbf{Flask}, almacenamiento en \textbf{SQLite} y un chatbot para responder consultas de matrícula y procesos académicos.
  \item Según la evaluación del proyecto, se redujeron en más de un 50\% las consultas directas a secretaría. \href{https://github.com/Katy-Bejar/EasyProcess}{Ver repositorio en GitHub}.
\end{itemize}

\project{BioVisualizer --- Análisis y visualización de secuencias biológicas}{2024}{Python, Flask, BioPython, NumPy, SciPy, HTML, CSS}
\begin{itemize}
  \item Implementé algoritmos de análisis de secuencias biológicas, clustering y visualizaciones interactivas para datos de proteínas, ADN y ARN.
  \item Integré procesamiento de datos en Python con una interfaz web. \href{https://github.com/Katy-Bejar/Visualizator}{Ver repositorio en GitHub}.
\end{itemize}

\project{Detección de enfermedades en hojas de tomate (Deep Learning)}{2024}{Python, PlantVillage, EfficientNetV2, ResNet50V2, DenseNet121}
\begin{itemize}
  \item Entrené y comparé modelos de aprendizaje profundo mediante transfer learning, fine-tuning y preprocesamiento de imágenes.
  \item Generé reportes automatizados de métricas y resultados. \href{https://github.com/Katy-Bejar/Enfermedades-en-las-hojas-de-las-plantas-de-tomate}{Ver repositorio en GitHub}.
\end{itemize}

\section{Educación}
\textbf{Universidad Nacional de San Agustín de Arequipa (UNSA)} \hfill 2020 -- Ene 2026\\[-1pt]
\textbf{Bachiller en Ciencia de la Computación} \quad|\quad Grado obtenido en mayo de 2026.

\section{Certificaciones}
\textbf{AWS Academy Cloud Foundations} \quad|\quad \textbf{AWS Academy Cloud Architecting}.

\section{Idiomas}
\textbf{Español:} nativo. \quad \textbf{Inglés:} intermedio (lectura y comprensión escrita). \quad \textbf{Portugués:} intermedio (comprensión y conversación).
\end{document}
