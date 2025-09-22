\documentclass[11pt,a4paper]{article}
\usepackage[margin=1.2cm,top=2cm]{geometry}
\usepackage{hyperref}
\usepackage{tabularx}
\usepackage{xcolor}
\usepackage{fontspec}
\usepackage{setspace}
\usepackage{enumitem}
\usepackage{ragged2e}
\usepackage{graphicx} % 插入图片支持
\usepackage{graphicx}  % 确保加载图片支持
\usepackage{array}     % 用于表格布局优化
\usepackage{tabularx}  % 自适应表格
\usepackage{adjustbox} % 使图片对齐
\usepackage{caption}   % 允许手动设置 caption
\captionsetup{skip=2pt} % 减少标题与图片之间的间距
% 字体与颜色配置
\definecolor{accent}{RGB}{0,82,147}
\setmainfont{Times New Roman}
\setsansfont{Arial}
\renewcommand{\familydefault}{\sfdefault}

% 紧凑列表格式
\setlist[itemize]{leftmargin=*,nosep,label=\color{accent}\textbullet}
\setlength{\parindent}{0pt}
\renewcommand{\baselinestretch}{1.05}

% 自定义章节格式
\usepackage{titlesec}
\titleformat{\section}{\sffamily\large\bfseries\color{accent}}
{\thesection}{0em}{}[{\titlerule[0.8pt]}]
\titlespacing*{\section}{0pt}{10pt}{6pt}

\begin{document}

% ============== 主标题 ==============
{\centering\sffamily\Huge\bfseries\color{accent}Curriculum Vitae\par}
\vspace{1.5em}  % 标题与页眉之间的间距

% ============== 页眉 ==============
\begin{center}
{\sffamily\LARGE\bfseries \textcolor{accent}{KeLi Qu}} \\[5pt]
\begin{tabular}{@{}c@{}}
Shandong University \quad | \quad\href{https://david71764.github.io/}{My Home Page}\\\
Phone: +86 173-9173-5297 \quad | \quad 
\href{mailto:keliqu@mail.sdu.edu.cn}{Email: keliqu@mail.sdu.edu.cn}\end{tabular}
\end{center}

% ============== 教育背景 ==============
\section*{Education}
\begin{tabularx}{\textwidth}{@{}X r@{}}
\textbf{City University of Hong Kong} & \textbf{2025.08.25--2025.12.23} \\
\sffamily Exchange student  \quad | \quad Major in Mathematics and Physics \\
\begin{itemize}
\item \textbf{Core Courses}: Applied Differential Geometry,Quantum Mechanics,RadioTherapy Physics
\item \textbf{Research Project}: QCNN for HEP data analysis,Applications of Reinforcement Learning in Quantum Computing and Quantum Information
\end{itemize}
\\
\textbf{Shandong University} & \textbf{2022.09--present} \\
\sffamily B.Sc. in Physics(Honors Class) \quad | \quad GPA: 88.64/100 \\
\multicolumn{2}{@{}p{\textwidth}@{}}{
\begin{itemize}
\item \textbf{Core Courses}:  Quantum Mechanics, Group Theory, Introduction to Experimental Methods in Particle Physics,Computational Physics and Experiment
\item \textbf{Research Project}: ATLAS experiment at the LHC,Thermal properties of ultra-wide bandgap semiconductor and thermal management of devices
\end{itemize}
} \\[8pt]
\end{tabularx}

% ============== 科研经历 ==============
\section*{Research Experience}
\begin{tabularx}{\textwidth}{@{}l X@{}}

06/2025--08/2025 & \textbf{Summer Research | Prof. WANG Xin Sunny} \\
& \textit{QCNN for High Energy Physics data analysis}
\begin{itemize}
\item Basic knowledge of quantum computing and quantum information
\item Familiar with Python library for QIQC and Quantum Machine Learning
\item As the demand for analyzing massive datasets in high-energy physics continues to grow, quantum machine learning has demonstrated quantum supremacy in certain problems, highlighting its increasing importance for data analysis in future high-luminosity LHC experiments.\par Inspired by the particle track identification algorithm used in the Deep Underground Neutrino Experiment (DUNE),using quantum convolutional neural network to construct a classifier for top quark jet image.
\end{itemize} \\[8pt]

09/2024--Present & \textbf{Research Project 2 | Prof. Yanlin Liu} \\
& \textit{ATLAS experiment at the LHC}
\begin{itemize}
\item Learned Python computational science and data analysis methods
\item Learn to use Boosted Decision Tree methods (implemented via XGBoost), develop a signal-to-background discrimination scheme to analyze the VBF and ggF processes of the $H\to\mu\mu$ in the ATLAS experiment.
\item Familiar with the workflow of working on the CERN Lxplus
\end{itemize} \\[8pt]



\end{tabularx}

\begin{tabularx}{\textwidth}{@{}l X@{}}


01/2024-06/2024 & \textbf{Research Project 1 | Prof. Jiayue Yang} \\
& \textit{Thermal properties of ultra-wide bandgap semiconductor and thermal management of devices}
\begin{itemize}
\item Basic knowledge of machine learning
\item Familiar with the use of LAMMPS(Large-scale Atomic/Molecular Massively Parallel Simulator)
\item Studied molecular dynamics and finite element methods in the research of microchannel heat dissipation and thermoelectric coupling of devices
\end{itemize}

\end{tabularx}

% ============== 技术能力 ==============
\section*{Lab Skills}
\begin{tabularx}{\textwidth}{@{}l X@{}}
\textbf{Quantum Computing and Quantum Information:} & Python library for QIQC and QML \\
\textbf{Particle Physics:} & Familiar with the workflow at CERN Lxplus and Gitlab \\
\textbf{Semiconductor Physics:} & Finite element analysis, Molecular dynamics simulation \\
\textbf{Programming Skills:} & Python,LAMMPS,Shell,Woalfram Mathematica
\end{tabularx}

% ============== 获奖与荣誉 ==============
\section*{Awards \& Honors}
\begin{tabularx}{\textwidth}{@{}l X@{}}
2025 & \textbf{Joint TDLI and INPAC Winter School in Particle Physics} \quad | \quad Successfully completed \\
2024 & \textbf{China Undergraduate Mathematical Contest in Modeling} \quad | \quad Second prize in Shandong province \\
2023 & \textbf{Algorithm Competition for College Students} \quad | \quad   Excellence Award in Group A\\
2022 & \textbf{Mathematics competition of Chinese College Student} \quad | \quad Third prize in Shandong province 
\end{tabularx}

% ============== 分页命令 ==============
\newpage

% ============== 附录 ==============
\section*{Appendix}
\begin{figure}[h]
    \centering
    \includegraphics[width=0.45\textwidth, angle=90]{1.jpg}
    \caption{2025 Joint TDLI and INPAC Winter School in Particle Physics}
\end{figure}

% 2,3 在左侧竖排，4 在右侧对齐
\begin{table}[h]
    \centering
    \renewcommand{\arraystretch}{1.1}  % 适当压缩行间距
    \setlength{\tabcolsep}{3pt}        % 减小列间距
    \begin{tabularx}{\textwidth}{X X}  % 左右两列排布
        % 左列（2,3 竖排）
        \begin{minipage}{0.4\textwidth}  % 略微缩小，保证在一页内
            \centering
            \includegraphics[width=0.75\textwidth]{3.jpg} \\
            \small 2024 China Undergraduate Mathematical Contest in Modeling \\[0.8em]
            \includegraphics[width=0.75\textwidth]{4.jpg} \\
            \small 2022 Mathematics Competition of Chinese College Student
        \end{minipage} &
        
        % 右列（4）
        \begin{minipage}{0.4\textwidth}
            \centering
            \includegraphics[width=0.9\textwidth]{2.jpg} \\
            \small 2023 Algorithm Competition for College Students
        \end{minipage} \\
    \end{tabularx}
   
\end{table}



\end{document}
