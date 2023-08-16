\documentclass[letterpaper,11pt]{article}
\newlength{\outerbordwidth}
\pagestyle{empty}
\raggedbottom
\raggedright
\usepackage[svgnames]{xcolor}
\usepackage{framed}
\usepackage{times}
\usepackage{tocloft}
\usepackage{graphicx}
\usepackage{multirow}
\usepackage[utf8]{inputenc}
\usepackage{tabularx}
\title{Aparna-CV}
%-----------------------------------------------------------
%Edit these values as you see fit

\setlength{\outerbordwidth}{3pt}  % Width of border outside of title bars
\definecolor{shadecolor}{gray}{0.75}  % Outer background color of title bars (0 = black, 1 = white)
\definecolor{shadecolorB}{gray}{0.93}  % Inner background color of title bars


%-----------------------------------------------------------
%Margin setup

\setlength{\evensidemargin}{-0.25in}
\setlength{\headheight}{0in}
\setlength{\headsep}{0in}
\setlength{\oddsidemargin}{-0.25in}
\setlength{\paperheight}{11in}
\setlength{\paperwidth}{8.5in}
\setlength{\tabcolsep}{0in}
\setlength{\textheight}{9.5in}
\setlength{\textwidth}{7in}
\setlength{\topmargin}{-0.3in}
\setlength{\topskip}{0in}
\setlength{\voffset}{0.1in}


%-----------------------------------------------------------
%Custom commands
\newcommand{\resitem}[1]{\item #1 \vspace{-2pt}}
\newcommand{\resheading}[1]{\vspace{8pt}
  \parbox{\textwidth}{\setlength{\FrameSep}{\outerbordwidth}
    \begin{shaded}
\setlength{\fboxsep}{0pt}\framebox[\textwidth][l]{\setlength{\fboxsep}{4pt}\fcolorbox{shadecolorB}{shadecolorB}{\textbf{\sffamily{\mbox{~}\makebox[6.762in][l]{\large #1} \vphantom{p\^{E}}}}}}
    \end{shaded}
  }\vspace{-5pt}
}
\newcommand{\ressubheading}[4]{
\begin{tabular*}{6.5in}{l@{\cftdotfill{\cftsecdotsep}\extracolsep{\fill}}r}
		\textbf{#1} & #2 \\
		\textit{#3} & \textit{#4} \\
\end{tabular*}\vspace{-6pt}}
%-----------------------------------------------------------


\begin{document}

%-----------------------------------------------------------
%Insert IIT Madras Logo 
\begin{tabular*}{7in}{l@{\extracolsep{\fill}}r}
  & \multirow{4}{*}{\includegraphics[scale=0.35]{uc.png}}\\
  & \\
%-----------------------------------------------------------  
  \textbf{\Large Juan Sebastian Palacio Prieto $|$ 1021512478 } & \\
   & \\
+57 3106375543 \\
  Bogota D.C  \\
  jpalaciop1@ucentral.edu.co \\
\end{tabular*}
\\


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\resheading{Datos Personales}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{itemize}
\item
	\ressubheading{Fecha de nacimiento}{5 septiembre}{}{ del 2004}
	\begin{itemize}
		
	\end{itemize}

\item
	\ressubheading{Nacionalidad}{}{Colombia}{}
	\begin{itemize}
		\resitem{Naci en la capital de Colombia (Bogota)}
	\end{itemize}
\end{itemize}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\resheading{Experiencia laboral}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
  \begin{center}
  \parbox{6.762in}{Hasta el momento no e tenido ninguna experiencia laboral dentro de mi proceso academico.}
  \end{center}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\resheading{Educacion}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{itemize}
\item
	\ressubheading{Primaria}{}{Gimnsaio Monseñor Manuel Maria Camargo}{2010-2014}
	

\item 
	\ressubheading{Bachiller}{}{Gimnsaio Monseñor Manuel Maria Camargo}{2015-2021}
	

\item
	\ressubheading{Pregrado}{}{Universidad Central}{2022-Actualmente}
	\begin{itemize}
		\resitem{Estudiante de ingenieria de sistemas.}
	\end{itemize}
\end{itemize}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\resheading{Habilidades}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{itemize}
\item
	Paciencia
	

\item
	Comunicación
	

\item
	Flexibilidad.

\item
    Respeto.
\end{itemize}

\end{document}
