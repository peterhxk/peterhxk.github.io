---
layout: default
title: Home
---

## **Greetings!**

I am a Computer Engineering student at McGill University with a passion in Cloud, System Design, Data, and Quant.

### **Experiences**

<div class="interactive-grid">

{% capture drakkar_content %}

<ul>
  <li>As an assessment, successfully implemented a Lua-based XMT dissector in Wireshark to extract and decode stock trade information from captured PCAP network packets, streamlining analysis of financial data streams</li>
</ul>
{% endcapture %}
{% include experience-block.html 
   title="Incoming Hedge Fund Programmer" 
   company="Drakkar Capital" 
   date="Jan 2026 - Aug 2026" 
   tech="Python, C, Lua, Wireshark, XMT"
   content=drakkar_content %}

{% capture transport_content %}

<ul>
  <li>Transformed million-scale raw data in varied formats (docx, pdf, html) within the Data Lake into gold datasets in the Data Warehouse, built interactive Power BI dashboards for business intelligence and data analytical insights</li>
  <li>Engineered ETL pipelines with Databricks and Data Factory, leveraged DevOps for Git-based version control and CI/CD procedure</li>
  <li>Improved JSON-like raw data ETL process to optimize efficiency and time complexity by 90%</li>
</ul>
{% endcapture %}
{% include experience-block.html 
   title="Data Engineer Intern" 
   company="Transport Canada" 
   date="Sept 2025 - Dec 2025" 
   tech="Azure Databricks, Azure Data Factory, Azure DevOps, Power BI, Git, SQL, Python"
   content=transport_content %}

{% capture cloudact_content %}

<ul>
  <li>Developed automated LLM pipeline to monitor SEC RSS feeds and extract information from filings (Extraction S-1 filings reached 90% accuracy)</li>
  <li>Implemented document chunking and semantic chunk matching using word embeddings, designed formatted output retrieval</li>
  <li>Integrated PostgreSQL for structured data storage. Deployed scalable and reliable availability system on Render</li>
</ul>
{% endcapture %}
{% include experience-block.html 
   title="AI Developer Intern" 
   company="CloudAct CPA" 
   date="Aug 2025 - Sept 2025" 
   tech="NLP, LLM, Word Embeddings, PostgreSQL, Render, RAG, LangChain, BeautifulSoup"
   content=cloudact_content %}

{% capture coinchain_content %}

<ul>
  <li>Architected end-to-end AWS Cloud solutions, optimizing cost, performance, security, and scalability using VPC design (public/private subnets, NAT gateways, Internet gateways), EC2, S3, RDS, IAM, CloudFront, and Route 53</li>
  <li>Supported companies in listing and managing SaaS, AMI, and container products on the AWS Marketplace, including setup of billing, metering, and deployment configurations</li>
</ul>
{% endcapture %}
{% include experience-block.html 
   title="Cloud Architect Intern" 
   company="Coinchain Inc." 
   date="May 2025 - Aug 2025" 
   tech="AWS, VPC, EC2, S3, RDS, IAM, CloudFront, Route 53"
   content=coinchain_content %}

{% capture tutor_content %}

<ul>
  <li>Conducted tutoring sessions for 10+ students in Calculus, Mechanics, E&M, and Computer Programming</li>
</ul>
{% endcapture %}
{% include experience-block.html 
   title="Collegial Level Tutoring" 
   company="Marianopolis College & Private Tutor" 
   date="Sept 2023 - Current" 
   tech="Calculus, Physics, Programming"
   content=tutor_content %}

</div>

### **Projects**

<div class="interactive-grid">

{% capture mood_content %}

<p><strong>Tech:</strong> Python, PyTorch, OpenCV, ResNet-152</p>
<ul>
  <li>Fine-tuned ResNet-152 on emotion detection dataset for real-time facial expression recognition</li>
  <li>Implemented live camera feed integration with visual effects based on detected emotions</li>
</ul>
<p><a href="https://github.com/peterhxk/CodeML_Hackathon_2025" target="_blank">View on GitHub</a></p>
{% endcapture %}
{% include project-block.html 
   title="MoodDetector" 
   meta="ResNet-152, Live Camera Feed"
   content=mood_content %}

{% capture itrack_content %}

<p><strong>Tech:</strong> JavaScript, Chrome Extension API, Google Sheets API</p>
<ul>
  <li>Developed a Chrome extension that automatically tracks job applications to a Google Sheet</li>
  <li>Implemented automatic data extraction from job posting pages</li>
</ul>
<p style="text-align:center; margin-top: 1rem;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/KrnUM2nuuWE" frameborder="0" allowfullscreen style="max-width: 100%;"></iframe>
</p>
{% endcapture %}
{% include project-block.html 
   title="ITrackApply Google Extension" 
   meta="Chrome Extension"
   content=itrack_content %}

{% capture scraper_content %}

<p><strong>Tech:</strong> Python, BeautifulSoup, Web Scraping</p>
<ul>
  <li>Scrapes 2500+ articles per hour from New York Times Magazine</li>
  <li>Records data in JSONL format for ML purposes</li>
</ul>
<p><a href="https://github.com/peterhxk/ScrapeNYT" target="_blank">View on GitHub</a></p>
{% endcapture %}
{% include project-block.html 
   title="NY Times Magazine Scraper" 
   meta="Web Scraping, Python"
   content=scraper_content %}

</div>

For more of my experiences, please check out my **CV**!!

In my free time, I enjoy **gaming**, playing **basketball** and cooking **homemade cuisine**!
