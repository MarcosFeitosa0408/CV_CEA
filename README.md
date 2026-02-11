from reportlab.platypus import SimpleDocTemplate, Paragraph, Spacer
from reportlab.lib.styles import getSampleStyleSheet
from reportlab.lib.pagesizes import letter
from reportlab.lib.units import inch

styles = getSampleStyleSheet()
style = styles["Normal"]
style.leading = 14

content = f"""
CURRÍCULO – MARCOS ANTÔNIO FEITOSA<br/><br/>

Estágio em Dados | Power BI | Python | Automação | Logística<br/>
São Paulo – SP<br/>
E-mail: <a href="mailto:marcosfeitosa.analista@gmail.com">marcosfeitosa.analista@gmail.com</a><br/>
Telefone: (11) 95224-7141<br/>
LinkedIn: <a href="https://www.linkedin.com/in/marcosfeitosa-analista/">Perfil no LinkedIn</a><br/>
GitHub: <a href="https://github.com/MarcosFeitosa0408">github.com/MarcosFeitosa0408</a><br/>
Portfólio: <a href="https://cosmicdata-reywmdpy.manus.space/">Abrir Portfólio</a><br/><br/>

OBJETIVO<br/>
Estágio em Dados | Power BI | Automação | Logística.<br/>
Aplicar minha experiência em operações e minha formação técnica em análise de dados para apoiar times de performance, automação e eficiência operacional.<br/><br/>

SOBRE MIM<br/>
Sou estudante de ADS e MBA em Data Analytics, BI & Big Data. Após 15 anos na logística, desenvolvi disciplina, visão operacional e foco em resultados — habilidades que aplico em análises, indicadores e automações.<br/><br/>

COMPETÊNCIAS<br/>
- Power BI: Modelagem, DAX, dashboards.<br/>
- Excel Avançado: Power Query, automações.<br/>
- SQL Server: JOIN, CTE, queries analíticas.<br/>
- Python: Pandas, automação de relatórios.<br/>
- Power Automate & Microsoft Lists.<br/>
- SharePoint e Microsoft Lists<br/>
- ETL básico, APIs, limpeza e cruzamento de dados.<br/><br/>

PROJETOS<br/>
- Dashboard Logístico em Power BI.<br/>
- Automação de relatórios com Python.<br/>
- Excel Interativo com Power Query.<br/>
- Modelagem e análises SQL (Contoso, bases internas).<br/><br/>

EXPERIÊNCIA PROFISSIONAL<br/>
Motorista Profissional (15 anos)<br/>
Transporte de cargas, cumprimento de SLA, atendimento e disciplina operacional.<br/>
Habilidades desenvolvidas: responsabilidade, trabalho em equipe, tomada de decisão e foco em performance.<br/><br/>

FORMAÇÃO<br/>
MBA em Análise de Dados, BI & Big Data – UNICID (Cursando)<br/>
Tecnólogo em Análise e Desenvolvimento de Sistemas – UNICID (Concluído)<br/><br/>

CURSOS<br/>
- Inteligência Artificial Impressionador<br/>
- SQL Impressionador<br/>
- Excel Impressionador<br/>
- Power BI Impressionador<br/>
- Python Automação<br/>
- Introdução ao Mundo de Dados – DIO<br/>
- Modelagem e BI – Simplifica<br/>
- Fuenc/Microsoft – IA aplicada<br/><br/>

PRETENSÃO PARA ESTÁGIO<br/>
A combinar / Conforme política da empresa<br/>
"""

doc = SimpleDocTemplate("/mnt/data/Curriculo_Marcos_Feitosa_Final.pdf", pagesize=letter)
story = []

story.append(Paragraph(content, style))

doc.build(story)

"/mnt/data/Curriculo_Marcos_Feitosa_Final.pdf"
Resultado
'/mnt/data/Curriculo_Marcos_Feitosa_Final.pdf'
# CV_CEA
Curriculo para CEA
