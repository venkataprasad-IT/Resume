# Resume
I used this LaTeX code to create my well-structured resume. I have uploaded my professional accounts and Educational details.

\documentclass[letterpaper,11pt]{article}


\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\usepackage{graphicx}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


\RequirePackage{tikz}
\RequirePackage{xcolor}
\RequirePackage{fontawesome}
\usepackage{tikz}
\usetikzlibrary{svg.path}




\definecolor{cvblue}{HTML}{0E5484}
\definecolor{black}{HTML}{130810}
\definecolor{darkcolor}{HTML}{0F4539}
\definecolor{cvgreen}{HTML}{3BD80D}
\definecolor{taggreen}{HTML}{00E278}
\definecolor{SlateGrey}{HTML}{2E2E2E}
\definecolor{LightGrey}{HTML}{666666}
\colorlet{name}{black}
\colorlet{tagline}{darkcolor}
\colorlet{heading}{darkcolor}
\colorlet{headingrule}{cvblue}
\colorlet{accent}{darkcolor}
\colorlet{emphasis}{SlateGrey}
\colorlet{body}{LightGrey}






%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}


% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}




% \pagestyle{fancy}
% \fancyhf{}  % clear all header and footer fields
% \fancyfoot{}
% \renewcommand{\headrulewidth}{0pt}
% \renewcommand{\footrulewidth}{0pt}


% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}


\urlstyle{same}


\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}


% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]


% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1


%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}


\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}


\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{\large#1} & \textbf{\small #2} \\
      \textit{\large#3} & \textit{\small #4} \\
     
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}




\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}


\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}


\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}


\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}




\newcommand\sbullet[1][.5]{\mathbin{\vcenter{\hbox{\scalebox{#1}{$\bullet$}}}}}


%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%




\begin{document}


%----------HEADING----------




\begin{center}
    {\Huge \scshape Sampati Rao Venkataprasad} \\ \vspace{2pt}
    Tekkkali,Andhrapradesh \\ \vspace{1pt}
    \small \href{tel:+xxxxxxxxxxxx}{ \raisebox{-0.2\height}\faPhone\ \underline{+91-7207124047} ~} \href{mailto:yourname@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{mrvenkattt@gmail.com}} ~
    \href{https://www.linkedin.com/in/venkata-prasad-3354b52a0/}{\raisebox{-0.3\height}\faLinkedinSquare\ \underline{Venkata Prasad}}  ~
    \href{https://github.com/venkataprasad-IT?tab=repositories}{\raisebox{-0.2\height}\faGithub\ \underline{Github}} ~
    \href{https://leetcode.com/u/mrvenkattt/}{\raisebox{-0.2\height}{\includegraphics[height=0.3cm, width=0.3cm]{leetcode.png}}\ \underline{LeetCode}} ~
    \vspace{-8pt}
     
\end{center}




%-----------EDUCATION-----------
 \section{EDUCATION}
\resumeSubHeadingListStart
  \resumeSubheading
    {GMRIT}{ 2023 --  2026}
    {B.Tech - Information Technology  - \textbf{CGPA} - \textbf{9.0}}{Rajam, India}
\resumeSubHeadingListEnd

\vspace{-10pt}%   Adjust this value to control the space between the subheadings

\resumeSubHeadingListStart
  \resumeSubheading
    {Andhra Polytechnic}{ 2020 --  2023}
    {B.Tech - Diploma in Computer Engineering  - \textbf{Percentage} - \textbf{7.6\%}}{Kakinada, India}
\resumeSubHeadingListEnd

 


%------RELEVANT COURSEWORK-------
\section{COURSEWORK / SKILLS}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-2pt, parsep=5pt]
                \item Data Structures \& Algorithms
                \item Operating Systems
                \item Network Security
                \item Database Management System (DBMS)
               \item Artificial Intelligence
                \item OOPS Concept
                \item Web Development
                \item Android Development
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd






%-----------PROJECTS-----------
\section{PROJECTS}
    \vspace{-5pt}
    \resumeSubHeadingListStart
       \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About project \textbf{key points to highlight}.}}


            \resumeItem{\textcolor{accent} {\href{Live Project Link} {\underline{\normalsize{Live site here}}}}}
          \resumeItemListEnd
          \vspace{-13pt}
         
      \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About project \textbf{highlight key points}.}}
            \resumeItem{\textcolor{accent} {\href{Project Link} {\underline{\normalsize{Download}}}}}
          \resumeItemListEnd
          \vspace{-13pt}
         
          \resumeProjectHeading
          {\href{ProjectLink.com}{\textbf{\large{\underline{Project Name}}} \href{Project Link}{\raisebox{-0.1\height}\faExternalLink }} $|$ \large{\underline{Technology Stack Used}}}{MM YYYY}
          \resumeItemListStart
            \resumeItem{\normalsize{About Project \textbf{highlight key points} }}
           
          \resumeItemListEnd
         
    \resumeSubHeadingListEnd
\vspace{-12pt}


%




%-----------EXPERIENCE-----------
\section{INTERNSHIP}
  \resumeSubHeadingListStart


    \resumeSubheading
      {Company Name \href{certificate Link}{\raisebox{-0.1\height}\faExternalLink }}{MM YYYY -- MM YYYY}
      {\underline{Role Name}}{city, country}
      \resumeItemListStart
        \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
 
      \resumeItemListEnd  
  \resumeSubHeadingListEnd
\vspace{-12pt}
%-----------PROGRAMMING SKILLS-----------
\section{TECHNICAL SKILLS}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textbf{\normalsize{Languages:}}{ \normalsize{Python, Java, C, C++, Dart, JavaScript, SQL, NoSQL, R, XML, Go}} \\
     \textbf{\normalsize{Developer Tools:}}{ \normalsize{VS Code, Android Studio, DataGrip, Goland, Intellij Idea Ultimate}} \\
     \textbf{\normalsize{Technologies/Frameworks:}}{\normalsize{ Linux, GitHub, ReactJS, Redux, NextJS, NodeJS, ExpressJS, Git, Mongo, Flutter}} \\
    }}
 \end{itemize}
 \vspace{-15pt}




%-----------INVOLVEMENT---------------
\section{EXTRACURRICULAR}
    \resumeSubHeadingListStart
        \resumeSubheading{Organization Name \href{Certificate Proof link}{\raisebox{-0.1\height}\faExternalLink } }{MM YYYY -- MM YYYY}{\underline{Role}}{Location}
            \resumeItemListStart
                \resumeItem{\normalsize{About the role \textbf{and responsibilities carried out.}}}
                \resumeItem{\normalsize{Participation Certificate. \href{ParticipationCertificateLink.com}{\raisebox{-0.1\height}\faExternalLink }}}
            \resumeItemListEnd
    \resumeSubHeadingListEnd
 \vspace{-11pt}
 
 %-----------CERTIFICATIONS---------------
\section{CERTIFICATIONS}


$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{ReactJS \& Redux - Udemy}} \hspace{1.6cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{Java}} \hspace{2.59cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com} {Command Line in Linux - Coursera}}\\


$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Python for Data Science - XIE}} \hspace{1cm}
$\sbullet[.75] \hspace{0.1cm}$ {\href{certificateLink.com}{SQL}} \hspace{2.6cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{Microsoft AI Classroom - Microsoft}} \\


$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{\textbf{5 Stars} in \textbf{C++} \& \textbf{SQL} \href{certificateLink.com}{\raisebox{-0.1\height}\faExternalLink }}}\hspace{1.45cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{MongoDB Basics}} \hspace{0.5cm}
$\sbullet[.75] \hspace{0.2cm}${\href{certificateLink.com}{NodeJS with Express \& MongoDB - Udemy}} \\




\end{document}




