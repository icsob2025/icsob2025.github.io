---
layout: home
title: AI Paper Summaries & Podcasts
permalink: /summaries/
---

<style>
  :root {
    --ink:#0b1026;
    --muted:#4a536b;
    --card:#ffffff;
    --bg:#f6f8fc;
    --accent:#0e1b4d;
    --accent-2:#0ea89e;
    --shadow:0 12px 28px rgba(10,22,70,.08);
    --radius:14px;
  }

  body{font-family:Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; background:var(--bg); color:var(--ink)}
  .page{max-width:1100px; margin:0 auto; padding:32px 20px 60px}

  .hero{background:linear-gradient(135deg,#0e1b4d 0%,#1e3a8a 55%,#0ea89e 110%); color:#fff; padding:42px 32px; border-radius:20px; box-shadow:var(--shadow); text-align:center; margin-bottom:28px}
  .hero h1{margin:0 0 10px; font-size:clamp(28px, 4vw, 44px)}
  .hero p{margin:6px 0; opacity:.95}
  .hero a{color:#c5e8ff; font-weight:700}

  .podcast-grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(310px,1fr)); gap:18px}
  .podcast-card{background:var(--card); border:1px solid #e4e9f5; border-radius:var(--radius); box-shadow:0 12px 24px rgba(10,22,70,.06); padding:18px; display:flex; flex-direction:column; gap:12px}
  .podcast-card h3{margin:0; font-size:18px; color:var(--accent)}
  .summary{margin:0; color:var(--ink); font-size:15px; line-height:1.6}
  .meta{font-size:13px; color:var(--muted); display:flex; gap:8px; align-items:center; flex-wrap:wrap}
  .controls{display:flex; gap:12px; flex-wrap:wrap; align-items:center}
  audio{width:100%; max-width:380px; margin-right:auto}
  .btn{display:inline-block; background:var(--accent); color:#fff; padding:10px 14px; border-radius:10px; text-decoration:none; font-weight:700; box-shadow:0 8px 16px rgba(10,22,70,.08)}
  .btn:hover{background:#102868}
  .badge{background:var(--accent-2); color:#fff; padding:4px 10px; border-radius:999px; font-size:12px; font-weight:800}
  .error{color:#c1121f; font-size:13px; margin-top:4px}

  .notice{margin-top:20px; font-size:13px; color:var(--muted)}
</style>

<div class="page">
  <div class="hero">
    <h1>AI Paper Summaries & Podcasts</h1>
    <p>Quick AI-generated summaries with matching podcast audio for each ICSOB 2025 paper.</p>
    <p>Podcasts produced by our friends at <a href="https://living-knowledge.com/" target="_blank" rel="noopener">living-knowledge.com</a>.</p>
  </div>

  <div id="podcastList" class="podcast-grid" aria-live="polite"></div>

</div>

<script id="podcast-data" type="application/json">
[
  {
    "id": "5740002",
    "program_id": "105",
    "title": "The Beauty and the Beast: Patterns and Anti-Patterns in use of Data",
    "summary": "About This study investigates how companies in the software-intensive systems industry manage and utilize the vast amounts of data collected from their products. Through a multi-case study of eight companies, the research identifies beneficial practices, or 'patterns', that lead to successful data use, and detrimental practices, or 'anti-patterns', that companies should avoid. Problem Companies are collecting ever-increasing volumes of data from their products but often struggle to effectively transform this raw data into customer and business value. There is a lack of practical guidance on what constitutes best practices, leading to significant challenges in data management, quality assurance, access control, and cost management. Study Outcome - Successful companies follow beneficial patterns such as: exploring new data-driven services at low cost on internal infrastructure, operating m",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740002.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740002.mp3"
  },
  {
    "id": "5740003",
    "program_id": "132",
    "title": "What Characterizes Data Spaces in Industry 4.0? Towards a Better Understanding",
    "summary": "About This study aims to clarify the defining features of data spaces within the Industry 4.0 context by developing a comprehensive classification system, or taxonomy. The researchers analyzed 19 existing data spaces to identify their common dimensions and characteristics, providing a structured way to understand and compare them. Problem As companies increasingly rely on data sharing for innovation in Industry 4.0, 'data spaces' have emerged as a key solution for secure collaboration. However, the concept is poorly defined, and the existing research is fragmented, making it difficult for businesses, especially small and medium-sized enterprises, to understand and engage with these new data ecosystems. Study Outcome - The study developed a taxonomy to classify data spaces, identifying nine key dimensions (like funding, key purpose, and underlying technology) and 40 distinct characteristi",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740003.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740003.mp3"
  },
  {
    "id": "5740004",
    "program_id": "185",
    "title": "What Are Digital Identities in Practice? Initial Insight from Finnish B2B Software Companies",
    "summary": "About This paper presents the initial findings from a qualitative interview study conducted with two Finnish business-to-business (B2B) software companies. The research goal was to understand how digital identities are perceived and managed from the perspective of identity providers and software product companies. The study identifies key stakeholder priorities, as well as the factors that disrupt or accelerate the process of meeting those priorities. Problem Software companies that provide software-as-a-service products must manage the growing complexity of digital identities, balancing numerous stakeholder needs and evolving regulations. There is a research gap in understanding how these companies practically define and handle digital identities, navigate competing priorities like security and user experience, and address challenges in a real-world business context. Study Outcome - Sof",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740004.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740004.mp3"
  },
  {
    "id": "5740005",
    "program_id": "144",
    "title": "Engineering Data Architectures for AI/ML Integration in Regulated Manufacturing",
    "summary": "About This study investigates the challenges and opportunities of integrating Artificial Intelligence (AI) and Machine Learning (ML) in regulated manufacturing sectors like pharmaceuticals and medical devices. Through 20 qualitative interviews with data architects, AI specialists, and compliance officers, the research identifies key barriers and proposes a conceptual framework for designing compliant, AI-driven data architectures. Problem Life science manufacturers are increasingly adopting AI/ML to improve production and compliance, but progress is slow. They face significant hurdles from fragmented data systems, legacy infrastructures, and data silos, which are compounded by complex and evolving regulatory requirements that create uncertainty around system validation and traceability. Study Outcome - Current data infrastructures in regulated manufacturing are highly fragmented, with da",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740005.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740005.mp3"
  },
  {
    "id": "5740006",
    "program_id": "129",
    "title": "Trust in Practice: Evaluating Third-Party Software in Large Organisational Procurement",
    "summary": "About This study investigates how large organizations evaluate and manage trust when procuring third-party software. Drawing from literature reviews and nine semi-structured interviews with professionals, the research identifies key trust factors and maps how they are applied throughout the procurement lifecycle. The goal is to provide practical insights for improving procurement strategies and for software vendors seeking to build trust. Problem As businesses increasingly depend on external software for core operations, the risk of supply chain attacks and data breaches has grown significantly. While trust in a software vendor is critical, there is limited understanding of how large organizations practically assess and maintain this trust beyond formal checklists. This study addresses the gap between prescribed procurement models and the real-world, dynamic processes companies use to ma",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740006.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740006.mp3"
  },
  {
    "id": "5740007",
    "program_id": "146",
    "title": "Simulating ERP Cyber Incidents: A Serious Game for Awareness and Incident Management",
    "summary": "About This paper presents the design, implementation, and evaluation of a serious game scenario titled 'ERP-Systems in Need' to raise cybersecurity awareness specifically for Enterprise Resource Planning (ERP) systems. The study applies a Design Science Research approach to build upon an existing game, simulating realistic security incidents to foster experiential learning. The game's effectiveness was evaluated in academic settings to measure its impact on increasing knowledge and preparedness for ERP-related cyber threats. Problem Enterprise Resource Planning (ERP) systems are fundamental to business operations but are increasingly vulnerable to sophisticated cyberattacks that can paralyze supply chains and cause significant financial damage. Traditional cybersecurity training methods like lectures are often ineffective at engaging users, and there is a lack of gamified training tools",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740007.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740007.mp3"
  },
  {
    "id": "5740008",
    "program_id": "165",
    "title": "The Ethical Requirements Stack: Operationalizing Adaptive Ethical Requirements with Human-AI Collaboration and GPT-based LLMs",
    "summary": "About This study introduces the Ethical Requirements Stack (ERS), a structured framework designed to translate high-level ethical principles into concrete development tasks for AI systems. Using a design science research methodology, the paper demonstrates a collaborative workflow where humans and GPT-based Large Language Models (LLMs) work together to elicit, decompose, and manage these ethical requirements in an Agile-inspired environment. Problem Software development teams often struggle to convert abstract ethical principles like fairness and transparency into specific, actionable requirements. This leads to an accumulation of \"ethical debt,\" where unresolved ethical issues create risks of reputational harm, regulatory penalties, and loss of stakeholder trust. Study Outcome - The study introduces the Ethical Requirements Stack (ERS), a practical framework for breaking down broad ethi",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740008.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740008.mp3"
  },
  {
    "id": "5740009",
    "program_id": "159",
    "title": "Addictive UX: Heuristic Evidence from Online Gambling UX and the Need for Ethical Guidelines",
    "summary": "About This study critically examines how online gambling platforms use specific User Experience (UX) design strategies to foster compulsive engagement and maximize user retention. Through a heuristic evaluation of five popular platforms, the research identifies and analyzes common persuasive and manipulative design patterns that exploit users' cognitive vulnerabilities. Problem The rise of online gambling has created a high-risk digital environment where sophisticated design techniques are used to encourage continuous play, often leading to compulsive behavior and addiction. There is a significant lack of transparency and ethical consideration in how these platforms are designed, exploiting user vulnerabilities for profit without implementing necessary protective measures. Study Outcome - A consistent and standardized set of UX design strategies focused on user retention was found across",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740009.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740009.mp3"
  },
  {
    "id": "5740010",
    "program_id": "161",
    "title": "Cost of Not Investing (CONI) in Intelligent Processes Automation",
    "summary": "About This study introduces and conceptualizes the 'Cost of Not Investing' (CONI) in intelligent process automation (IPA). The authors develop a framework identifying three dimensions of CONI\u2014operational inefficiencies, strategic disadvantages, and human capital impacts\u2014and test initial perceptions through a cross-sector survey of 108 professionals in the US and EU. Problem Traditional methods for evaluating technology investments fail to capture the significant strategic risks associated with delaying the adoption of AI-driven automation. This oversight can lead businesses to make suboptimal decisions by underestimating the cascading negative consequences of inaction, such as losing competitive advantages and key talent. Study Outcome - Delaying automation has severe consequences, with professionals identifying talent migration (81% agreement), lower productivity (77%), and loss of earl",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740010.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740010.mp3"
  },
  {
    "id": "5740011",
    "program_id": "174",
    "title": "Understanding Organizational Decision to Adopt AI Technologies: A Qualitative Study",
    "summary": "About This qualitative study investigates how organizations decide to adopt Artificial Intelligence (AI) technologies. Through 15 semi-structured interviews across various industries, the research applies Gioia's method to identify the key motivations, triggers, and decision-making factors influencing AI adoption. The study proposes a process model to explain this complex decision-making journey. Problem Many organizations struggle with the critical decision of when and how to adopt AI, often rushing into implementation without strategic clarity, which leads to disappointing results. Existing research models often overlook the complex, contextual processes through which organizations deliberate and evaluate AI, creating a gap in understanding the practical decision-making journey. Study Outcome - AI adoption is not a singular, technical decision but a complex, multi-stage reasoning proce",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740011.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740011.mp3"
  },
  {
    "id": "5740012",
    "program_id": "148",
    "title": "Investigating Generative AI's Impact on Software Organizations' Security Practices: A Multi-Case Study Using Gioia Methodology",
    "summary": "About This study investigates how generative AI can enhance software security practices through a multi-case study involving five different software organizations. Using semi-structured interviews with developers and managers, the research identifies key areas where AI can provide support, while also uncovering the sociotechnical risks that may hinder its adoption. Problem Software organizations face a rising number of security threats, and manual security processes are often time-consuming, error-prone, and expensive. While generative AI offers a promising solution to enhance security, its practical impact and the associated risks for software organizations remain largely underexplored. Study Outcome - Generative AI can enhance four key security practices: threat assessment, security testing, operational management, and education & guidance. - Significant sociotechnical risks impede AI",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740012.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740012.mp3"
  },
  {
    "id": "5740013",
    "program_id": "154",
    "title": "Recommended Features for Digital Reporting Systems to Support Emissions Disclosures for Small and Medium-Sized Enterprises",
    "summary": "About This study investigates the digital and workflow-related challenges that small and medium-sized enterprises (SMEs) face when collecting and reporting emissions data for Corporate Sustainability Reporting Directive (CSRD) compliance. Using a multi-method approach combining document analysis of regulatory standards and semi-structured interviews with SME professionals, the paper identifies key barriers and proposes features for digital reporting systems to address these issues. Problem New European Union regulations (CSRD) mandate extensive sustainability and emissions reporting, creating significant challenges for SMEs, which often lack the technical infrastructure, expertise, and resources to comply. There is a research gap concerning how these smaller companies can adopt or struggle with digital solutions to meet these demanding new requirements for collecting, measuring, and repo",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740013.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740013.mp3"
  },
  {
    "id": "5740014",
    "program_id": "166",
    "title": "A Thematic Analysis of Environmental Sustainability in Software-Intensive Business: Understanding Practices, Barriers, and Benefits",
    "summary": "About This study investigates how environmental sustainability is implemented in software-focused companies and identifies the factors that motivate or obstruct these green practices. The findings are based on a thematic analysis of 22 semi-structured interviews with 38 professionals from various Finnish organizations involved in Green ICT projects. Problem The software industry has a dual role in sustainability; it can enable efficiency and resource optimization, but it also contributes to a significant environmental footprint through energy consumption and hardware dependencies. Despite increased awareness, a persistent gap exists between research on sustainable practices and their actual implementation in business operations. Study Outcome - The primary barriers to implementing sustainable practices are low prioritization compared to cost or quality, unclear roles and responsibilities",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740014.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740014.mp3"
  },
  {
    "id": "5740015",
    "program_id": "126",
    "title": "Design Principles for IT-Driven Circular Economy Initiatives",
    "summary": "About This study aims to create clear guidelines for businesses looking to implement IT-supported circular economy (CE) projects. Using a mixed-methods approach that included a literature review, text analysis, and a workshop with industry practitioners, the researchers developed a set of core design principles. Problem While the circular economy is a popular concept, its broad and often vague definitions make it difficult for companies to implement practical, IT-driven initiatives. This lack of conceptual clarity hinders organizations from identifying effective strategies, preventing them from fully realizing the potential of IT to advance sustainability goals. Study Outcome - DP1: Regulatory and Goal Alignment for IT-Driven CE Initiatives: This principle ensures that projects comply with regulations and balance economic goals with clear ecological and social objectives. - DP2: Digital",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740015.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740015.mp3"
  },
  {
    "id": "5740016",
    "program_id": "134",
    "title": "Comparative Analysis of Generative AI Performance in University Programming Courses",
    "summary": "About This study evaluates how effectively five different Generative AI (GenAI) tools can complete exercises and quizzes in five university programming courses. The research objective was to measure and compare the performance of these AIs across different courses to understand their capabilities in an academic setting. The methodology involved using the GenAI tools to solve all weekly exercises, mimicking a student who relies solely on AI to pass. Problem The rise of powerful Generative AI presents a significant challenge to university education, particularly in programming, as students can potentially use these tools to complete assignments without genuine learning. This creates a gap in verifying student knowledge and skills, forcing educators to reconsider how courses are designed and assessed. The study addresses the urgent need to understand the exact capabilities of these AIs to a",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740016.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740016.mp3"
  },
  {
    "id": "5740017",
    "program_id": "170",
    "title": "Enhancing Agile Workflows with AI-Driven, Sustainability-Aware Requirements Engineering: A Design Science Approach",
    "summary": "About This study introduces Reqwire, an AI-driven, multi-agent system designed to integrate sustainability into agile software development. The system automatically generates user stories from requirement documents, enriches them with sustainability attributes, and integrates with project management tools like Jira. The research follows a Design Science Research (DSR) approach, using iterative cycles of design and evaluation with feedback from industry and academic partners. Problem During the requirements engineering phase of software projects, sustainability is often not a primary consideration. As a result, software engineers typically lack the tools to assess the environmental, social, and economic impacts of their products, leading to a gap between development practices and sustainable outcomes. This study addresses the lack of systematic tools for incorporating sustainability direc",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740017.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740017.mp3"
  },
  {
    "id": "5740018",
    "program_id": "141",
    "title": "Narrative AI Strategies for Media, Ethics and Higher Education Impulse Perspectives from Practice Based Media Education",
    "summary": "About This paper presents a conceptual framework for integrating Generative AI (GenAI) into higher education and corporate communication. Drawing on practice-based teaching experiences, it argues that the transformation driven by GenAI requires a threefold competence profile encompassing technical proficiency, narrative design, and ethical reflexivity. The study uses a conceptual approach based on media ethics, AI governance, and narrative theory to bridge the gap between academic theory and real-world business applications. Problem The rapid adoption of Generative AI is reshaping fundamental concepts like authorship, narration, and authenticity in media and academia. This presents a significant challenge for educational institutions and businesses, which must move beyond simple technical adoption to address the profound ethical, intellectual, and practical implications. The paper addres",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740018.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740018.mp3"
  },
  {
    "id": "5740019",
    "program_id": "181",
    "title": "The Role of AI in Software Release Management",
    "summary": "About This study examines how two types of AI, Analytical and Generative, can support decision-making in the software release process. Based on qualitative interviews with seven industry experts, the paper identifies the key benefits, hurdles, and practical applications of integrating AI into modern, fast-paced development environments. Problem In modern software development with rapid CI/CD cycles, release management has become increasingly complex, compressing decision windows and elevating risk. While Artificial Intelligence presents new tools to manage this complexity, significant practical challenges such as integration complexity, model opacity, and organizational resistance hinder its effective adoption. Study Outcome - AI integration offers key benefits including increased automation of repetitive tasks, more efficient resource allocation, enhanced risk forecasting, and improved",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740019.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740019.mp3"
  },
  {
    "id": "5740020",
    "program_id": "173",
    "title": "Active Personas for Synthetic User Feedback: A Design Science Study",
    "summary": "About This study evaluates the effectiveness of Active Personas (APs), which are user archetypes powered by Generative AI, in producing realistic user feedback for new product development. Using a Design Science Research approach, the researchers created APs based on different personas and Large Language Models (LLMs) to provide feedback on a mobile transport app. The AI-generated feedback was then compared against feedback from human users and Google Play reviews to assess its alignment and validity. Problem Securing consistent and diverse user feedback is a critical part of product development, but it is often a resource-intensive and time-consuming process. Development teams struggle to get rapid feedback from a wide range of user types, which can slow down innovation. This study explores whether AI-powered personas can serve as a low-cost, on-demand alternative to generate valuable u",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740020.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740020.mp3"
  },
  {
    "id": "5740021",
    "program_id": "163",
    "title": "Transitioning Towards Enterprise Architecture Management in a Software and Service Mobility Company: A Case Study",
    "summary": "About This paper presents a case study on implementing Enterprise Architecture Management (EAM) within a company shifting from hardware to software and services. The researchers developed a practical evaluation tool, a \"fitting matrix,\" by conducting expert workshops and interviews to help the company choose the most suitable EAM strategy. This matrix systematically compares various EAM implementation models based on key success criteria. Problem Companies today face rapid changes and growing complexity, making traditional management methods ineffective. While Enterprise Architecture Management (EAM) is a promising solution for creating a holistic organizational view, there's a lack of clear, practical guidance on how to select and implement the right EAM approach for a company's specific context. Study Outcome - Developed a practical assessment tool called a \"fitting matrix\" to help org",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740021.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740021.mp3"
  },
  {
    "id": "5740022",
    "program_id": "184",
    "title": "A Software-Driven Approach to Model, Simulate and Optimize Service-Oriented Value Creation",
    "summary": "About This study presents a software-supported approach designed to help businesses configure and manage complex, service-oriented value networks. The core of this approach is a detailed metamodel, implemented in a software tool, which integrates all relevant elements like partners, resources, and activities into a single data model. This allows companies to model, analyze, simulate, and optimize their collaborative service offerings. Problem As industries shift from product-centric to service-oriented models, businesses increasingly operate within complex networks of partners, suppliers, and customers. Traditional methods for business modeling are inadequate for managing the intricate, non-linear decisions required in these ecosystems, creating a need for a tool that can handle coordinated decision-making across the entire value network. Study Outcome - The developed software tool enabl",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740022.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740022.mp3"
  },
  {
    "id": "5740023",
    "program_id": "156",
    "title": "The Finnish Way to SaaS Scaling: A Qualitative Study",
    "summary": "About This paper investigates how software-as-a-service (SaaS) startups in Finland successfully scale their operations. Through a qualitative multiple-case study of six Finnish companies, the research develops an integrated model that examines the interplay between business, organizational, and engineering choices. The study identifies a coherent scaling strategy suited for companies operating in smaller, digitally advanced economies with limited domestic markets. Problem Scaling is a critical phase where many software startups fail, and existing research predominantly focuses on large, capital-rich ecosystems like Silicon Valley. This creates a knowledge gap regarding how startups navigate growth in smaller markets, such as Finland, which require early internationalization. The study addresses how these companies must integrate commercial, organizational, and technical strategies to ach",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740023.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740023.mp3"
  },
  {
    "id": "5740024",
    "program_id": "130",
    "title": "Democratising Work in the Software Sector: Insights on Cooperative Businesses",
    "summary": "About This study explores cooperative software businesses as an alternative model to address social-environmental crises and corporate short-termism. Researchers analyzed a dataset of 76 cooperative software firms and conducted interviews with members from 23 of them. The goal was to understand member motivations, democratic management practices, and the potential impact of this business model on the software sector. Problem Traditional corporate structures often focus on short-term financial gains, which can lead to negative social and environmental consequences. While cooperatives present a democratically managed alternative, software worker cooperatives have remained an under-explored area of research. This study addresses this gap by investigating their characteristics and potential for positive transformation in the tech industry. Study Outcome - Members of cooperative software busi",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740024.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740024.mp3"
  },
  {
    "id": "5740025",
    "program_id": "176",
    "title": "An AI-Driven Decision Support System for Product Feature Prioritization in Software Startups",
    "summary": "About This study investigates the potential of an AI-based decision support system for prioritizing product features within software startups. Using a design science research methodology, the authors developed a proof of concept (PoC) tool that uses AI to score features based on criteria like ROI and time-to-value. The PoC was then demonstrated to and evaluated by seven software entrepreneurs through semi-structured interviews to gauge its perceived usefulness and potential for adoption. Problem Software startups operate in fast-paced, uncertain environments with limited resources, making the prioritization of new product features a critical and constant challenge. Decisions are often made based on intuition or incomplete information, creating a need for more structured, data-driven approaches. This research addresses the gap by exploring how AI can enhance the feature prioritization pro",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740025.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740025.mp3"
  },
  {
    "id": "5740026",
    "program_id": "175",
    "title": "Accelerating Software-Intensive Innovation via Living Labs: Evidence from the AIAMO Project",
    "summary": "About This paper explores how 'Living Labs' can serve as effective frameworks for developing and testing artificial intelligence (AI) innovations in the mobility sector. Using the AIAMO (Artificial Intelligence And Mobility) research project as a case study, it demonstrates how these collaborative, real-world environments facilitate the creation of practical, user-centered AI applications for traffic management. Problem Developing and implementing complex AI technologies for real-world scenarios, like smart mobility, faces significant hurdles. There is a need for open, practical testing environments that involve diverse stakeholders to bridge the gap between lab-based research and market-ready solutions, ensuring innovations are both effective and accepted by users. Study Outcome - Infrastructure Requirements: Integrating AI systems effectively requires a dedicated, accessible, and inter",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740026.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740026.mp3"
  },
  {
    "id": "5740027",
    "program_id": "142",
    "title": "Balancing Power and Participation: Ethical Contributions to Digital Strategy Development Based on a Case Study at a Public University",
    "summary": "About This study explores how ethical considerations can be effectively integrated into the digital strategy development process within organizations. Through a qualitative case study at a German public university, researchers interviewed sixteen employees across various hierarchical levels to understand how ethics are perceived and can contribute to a more effective strategy by balancing power and participation. Problem As organizations undergo digital transformation, ethical concerns are often treated as secondary or are not effectively embedded in the strategy development process itself. This creates a gap where decisions about technology and resource allocation are viewed as purely technical, overlooking their inherent ethical dimensions and the central tension between centralized power and broad employee participation. Study Outcome - Ethics are often perceived as an individual's pe",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740027.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740027.mp3"
  },
  {
    "id": "5740028",
    "program_id": "168",
    "title": "Practical Adoption of Green Coding: A Comparative Study across Organizations in Finland and Globally",
    "summary": "About This study investigates how software development organizations in Finland and globally are practically adopting green coding practices. It uses a qualitative research method, combining a systematic literature review with semi-structured interviews with 15 software professionals to compare academic recommendations with real-world industry applications. Problem The Information and Communication Technology (ICT) sector has a significant and growing environmental footprint, contributing to global greenhouse gas emissions. While green coding offers a way to create more energy-efficient software, there is a notable gap between academic proposals and their practical adoption in the industry, leaving developers without standardized guidelines or integrated tools. Study Outcome - Organizations widely adopt practices that improve both performance and energy efficiency, such as caching, lazy",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740028.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740028.mp3"
  },
  {
    "id": "5740029",
    "program_id": "140",
    "title": "Playing Against Creative Burnout in Sprint Retrospectives: A Design Science Research Study",
    "summary": "About This study investigates how playful interaction design can mitigate creative burnout in software development teams' Sprint Retrospectives. Using a Design Science Research approach, the researchers developed and evaluated a design artifact called 'Scrumstinct' in workshops with eight professional teams to understand the impact of playfulness on team well-being and creativity. Problem Creative burnout is a significant issue in software development, leading to stagnation, exhaustion, and rigid routines that harm team creativity and well-being. While acknowledged in the industry, this phenomenon is academically underexplored, particularly at the team level, creating a need for research-backed strategies to foster sustainable creativity. Study Outcome - Playful retrospectives can successfully reframe problems, foster openness, and reduce emotional fatigue among software development team",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740029.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740029.mp3"
  },
  {
    "id": "5740030",
    "program_id": "169",
    "title": "Understanding Consumer Behavior and Sustainability Perception for Digital Technology Products and Services: Addressing End-users' Unmet Sustainability Concerns",
    "summary": "About This study investigates the sustainability perceptions and behaviors of consumers regarding digital technology products and services. Through a global survey of 490 technology end-users, the research identifies their key concerns, unmet expectations, and views on the current sustainability efforts of technology companies. Problem While there is extensive research on technology and sustainability, most of it focuses on the digital technologies themselves or the companies behind them, leaving a gap in understanding the end-user's perspective. This study addresses the lack of insight into consumer sustainability perceptions, behaviors, and expectations, which is crucial for promoting sustainable consumption in the digital economy. Study Outcome - Consumers' most pressing unmet sustainability needs are product durability, transparency, corporate legitimacy, ethical practices, the right",
    "pdf": "/assets/aI_summeries/pdfs/summary_5740030.pdf",
    "mp3": "/assets/aI_summeries/podcasts/5740030.mp3"
  }
]
</script>

<script>
  (function () {
    const dataNode = document.getElementById('podcast-data');
    const listNode = document.getElementById('podcastList');
    if (!dataNode || !listNode) return;

    let items;
    try {
      items = JSON.parse(dataNode.textContent);
      if (!Array.isArray(items)) throw new Error('Data is not an array');
    } catch (err) {
      listNode.innerHTML = '<div class="podcast-card"><p class="error">Could not load podcast data.</p><p class="error">' + err.message + '</p></div>';
      console.error('Podcast data load failed', err);
      return;
    }

    if (!items.length) {
      listNode.innerHTML = '<div class="podcast-card"><p class="error">No podcasts available yet. Please check back soon.</p></div>';
      return;
    }

    const trim = (text, limit = 260) => {
      const clean = (text || '').replace(/\s+/g, ' ').trim();
      return clean.length > limit ? clean.slice(0, limit - 1) + '...' : clean || 'No summary available.';
    };

    items.forEach((item) => {
      const card = document.createElement('article');
      card.className = 'podcast-card';
      card.dataset.id = item.id || '';

      const heading = document.createElement('h3');
      heading.textContent = item.title || 'Untitled';
      card.appendChild(heading);

      const meta = document.createElement('div');
      meta.className = 'meta';
      meta.innerHTML = '<span class="badge">Program ' + (item.program_id || 'n/a') + '</span><span>ID ' + (item.id || 'n/a') + '</span>';
      card.appendChild(meta);

      const summary = document.createElement('p');
      summary.className = 'summary';
      summary.textContent = trim(item.summary);
      card.appendChild(summary);

      const controls = document.createElement('div');
      controls.className = 'controls';

      if (item.mp3) {
        const audio = document.createElement('audio');
        audio.controls = true;
        audio.preload = 'none';
        audio.src = item.mp3;
        audio.setAttribute('aria-label', 'Podcast for ' + (item.title || 'paper'));
        controls.appendChild(audio);
      } else {
        const missing = document.createElement('span');
        missing.className = 'error';
        missing.textContent = 'Audio coming soon';
        controls.appendChild(missing);
      }

      if (item.pdf) {
        const pdfLink = document.createElement('a');
        pdfLink.className = 'btn';
        pdfLink.href = item.pdf;
        pdfLink.target = '_blank';
        pdfLink.rel = 'noopener';
        pdfLink.textContent = 'Read PDF Summary';
        controls.appendChild(pdfLink);
      }

      card.appendChild(controls);
      listNode.appendChild(card);
    });
  })();
</script>
