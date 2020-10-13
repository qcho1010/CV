---


---

<h1 id="table-of-contents">Table of Contents</h1>
<ul>
<li><a href="#mission-statement">1 Mission Statement</a></li>
<li><a href="#introduction">2 Introduction</a></li>
<li><a href="#ml-processing-from-start-to-finish">3 ML Processing from start to finish</a>
<ul>
<li><a href="#planning">3.1 Planning</a></li>
<li><a href="#formulation">3.2 Formulation</a></li>
<li><a href="#modeling">3.3 Modeling</a></li>
<li><a href="#production">3.4 Production</a></li>
<li><a href="#post-production">3.5 Post Production</a></li>
</ul>
</li>
<li><a href="#lessons-learned-&amp;-common-pitfalls">4 Lessons Learned &amp; Common Pitfalls</a></li>
<li><a href="#core-competencies">5 Core Competencies</a></li>
<li><a href="#other-competitors">6 Other Competitors</a></li>
</ul>
<h1 id="mission-statement">1 Mission Statement</h1>
<p>The purpose of this document is to help the reader to understand the ML without any prior knowledge from high level algorithms all the way to business use cases. Target audiences are Data Scientists, Cloud Architects, Product Managers, and Sales representatives</p>
<h1 id="introduction">2 Introduction</h1>
<p>Machine learning provides an alternative paradigm for developing capabilities. For conventional programming, a program is developed explicitly using one of multiple programming languages. With machine learning, the program is created implicitly using data. For machine learning, a computer can learn a specific task without being explicitly programmed to perform that task.</p>
<p><img src="https://lh6.googleusercontent.com/RLPVpABwhGDtaCRJJew7lo35zRXrwcp9pcSPTPmgXx9_3_rEU3pGjdsFUpAIQc81PFTm-0-59xd0cjuK4Bn2DDgtqySShVLE9XH_v5axy4SM96QoYDoSqSsHNDn5_OQLM0sJ8d-l" alt=""></p>
<p>As the chart below shows, different problems can be solved using different types of algorithms or combinations of multiple algorithms. One of the most critical processes of data science is asking right questions to solve that impact the business. Based on the questions asked, we can experience the possible algorithms to find the most optimal solution.</p>
<p><img src="https://lh5.googleusercontent.com/2rU2Xr4GKAVP0pZHjQVp_a4MMSQx_5GkI0NVLHGuyizxZObkGvtLhegPI5bbU-Q0y_hx42X1vufVHwK5H12QQEfKP2XhIyaZ2DWfptBi1rDoAup9FHEpJ7RBG0JMIoSkcGAgWLsk" alt=""></p>
<p><img src="https://lh6.googleusercontent.com/7DfZHdJpvEQCxyajYoBjCA3Ty7FYBzE2ZOKmaSNl5RRzTz1UqhcVCXp1hEaW2pepGVDkbwxMrRjoU8vL5dw4ii7qjZUle83Us9Rdt8ZOOgERcLVTC7almg3Jwf-nCYoT-1M3aQSY" alt=""></p>
<h1 id="ml-processing-from-start-to-finish">3 ML Processing from start to finish</h1>
<p>The ML team is composed of individuals with various skill sets. Business leader who communicates with clients at a high-level and strategizes the plan and resources to successfully deliver the promises. Technical leader to collaborate with other technical team members to address any technical obstacles or challenges and plan out the technical roadmap to the final products. Data Engineer who is responsible for efficient ETL process as well as the deployment of model pipelines once it’s built. Data Scientist who is responsible for completing dots from asking questions to building powerful models.</p>
<p>The following are some of the primary skills required by the machine learning and data science domain to support an engagement. These skills are broken down into 5 high level categories: planning, formulation, modeling, production, and post production.</p>
<h2 id="planning">3.1 Planning</h2>
<p>For planning activities the key parameters that need to be considered are how to generate business insights, increase collaboration, foster teamwork, planning the effort, and prototyping alternatives. The following activities are relevant in this phase:</p>
<ul>
<li>Business problem/opportunity definition and understanding</li>
<li>Quantifying business value and defining key metrics</li>
<li>Assessing computation resource requirements</li>
<li>Defining key milestones and timeline</li>
<li>Addressing data security, privacy requirements</li>
<li>Performing a legal review</li>
</ul>
<h2 id="section"><img src="https://lh3.googleusercontent.com/6SzLwz3kpS6gWoi9504sOhmI3oot6LCxX_UnUjlUAULfJ6Vjg7naU0cKlCDnLIZA4v1ub8mFpIu36tgAc47r1OeZE13zzDHZPjKxoEoqP1T6ohSn4SG0i4hMbYjpetL6ksqOeq-A" alt=""></h2>
<h2 id="formulation">3.2 Formulation</h2>
<p>In the formulation phase of an effort the emphasis is on:</p>
<ul>
<li>Statistical / ML thinking</li>
<li>Idea abstraction</li>
<li>The process for data generation</li>
<li>Understanding the data</li>
<li>Preprocessing the data</li>
<li>Exploring feature engineering ideas</li>
</ul>
<p>Some of the primary technical tools that are used in this phase are:</p>
<ul>
<li>SQL</li>
<li>Python (pandas)</li>
<li>R (especially the tidyverse package)</li>
<li>PySpark / SparkR</li>
</ul>
<p><img src="https://lh5.googleusercontent.com/EzV1XmWR0y2rhtbDHCHVcM-l_nzPIHEJatsSBGIp3z3r0zxxWfuqNrZcU2XEw-QMbHEYzfJjqw7EBmvCdcHXMH-dj19WAP1MpcNFmUoz4UpPb8KmpMhCgdSMmzp1FlblC7394GoE" alt=""></p>
<h2 id="modeling">3.3 Modeling</h2>
<p>During the modeling effort, traditional machine learning methods are employed. This is where techniques for general model training and tuning are performed - especially when deep learning methods are used. The primary tasks performed in this phase include:</p>
<ul>
<li>Model exploration and development</li>
<li>Model training, validation and testing</li>
<li>Model selection</li>
</ul>
<p>Some of the primary technical tools that are used in this phase are:</p>
<ul>
<li>Scikit Learn</li>
<li>Deep learning libraries such as Pytorch, Tensorflow, and Keras</li>
<li>Spark MLib</li>
<li>Probabilistic machine learning libraries such as pymc3, and Edward</li>
</ul>
<p><img src="https://lh3.googleusercontent.com/rgFwO_wVTZANmty1UjzfaSm-ALBkgehjk5KdSOASrFsFsFnxS-t35wn3c268RbqGI5NXCJV2EnBQqePHPZU6sqCCnTHxPW_Po-jnhPpP1jnWb5X5C5D7cSNiqH49_-T7t3jHMUeX" alt=""></p>
<h2 id="production">3.4 Production</h2>
<p>Once an ML capability has been developed and models have been produced, they will need to be placed into a production environment that will require a scalable deployment, performance and fault monitoring, fault-tolerance, maintenance and updates. Some of the tasks will include creation of a production quality system, creation of support for testing, development and execution of a plan for launching and updating the deployed components, support for monitoring performance, deployment as services that can be invoked from other systems and perhaps a dashboard or user interface to access the capabilities provided by the developed models.</p>
<p>Some of the primary technical tools that are used in this phase are:</p>
<ul>
<li>Tableau</li>
<li>R-Shiny</li>
<li>GCP components such as DataFlow, Cloud Functions, BigQuery</li>
</ul>
<p><img src="https://lh5.googleusercontent.com/gk4UxdUNLelJtwDrK19Fu8XZ_BOeTthLe0xVCntH6fF7n7UIDeppPwJCuykQcGhBID0WMhtR3803rR690BQOzVWKbEcZ3HK9KXpWXBqkJ92u9B3jQvG0lWN_COsDbPa12MbpVIum" alt=""></p>
<h2 id="post-production">3.5 Post Production</h2>
<p>Once the system is in production and has been leveraged, there will ultimately be the need to tune the models, retrain the models with newly collected data from the production system or from other sources, and perhaps even the replacement of the model when an alternative approach is discovered, or if the model does not continue to provide satisfactory results.</p>
<p>Some of the primary technical tools that are used in this phase are:</p>
<ul>
<li>AutoML</li>
</ul>
<p><img src="https://lh5.googleusercontent.com/td7rSmhkd1hoJvdJxQcOIVtYLIS7pDndB80Ikd2EoTaTvN_Bvxxv8_jfZHYmEDMYFalFr_EE4zpKtQH2SMD7zIltFEXlnannzelNFosfARtBN2pGfHyHXCaZodAc9gxmur4LxS_5" alt=""></p>
<p>Here is another perspective on the GCP tools that are required in the various phases of an ML project.</p>
<p><img src="https://lh6.googleusercontent.com/4MI1VXl9AXC5Rxie7ioMb7o3GaO6YAqDf27ddL1Kq6eQwlSTlYQfZ_BvUiXVrHPuIh3zZr3e2EnOKXHsf7QCkz4NYwU5Nj-2XaYm1ufHhnp3ZKYpkDu9Rl8U_g08Qf14ngRrFP5w" alt=""></p>
<h1 id="lessons-learned--common-pitfalls">4 Lessons Learned &amp; Common Pitfalls</h1>
<p>Some common pitfalls in ML and Data Science projects:</p>
<p><strong>Project Planning Stage</strong></p>
<ol>
<li>Solving the wrong problem
<ul>
<li>Vague description of business needs</li>
<li>Scientist team are actively participating in the problem formulation process</li>
</ul>
</li>
<li>Too optimistic about the timeline
<ul>
<li>Many ML method-specific uncertainties are not account for at planning stage</li>
</ul>
</li>
<li>Over promise on business value
<ul>
<li>Unrealistic high expectation</li>
<li>Many assumptions about the project are usually not true</li>
</ul>
</li>
</ol>
<p><strong>Project Formulation Stage</strong></p>
<ol>
<li>Too optimistic about standard statistical and ML methods
<ul>
<li>Extra efforts are needed to abstract business problem into a set of analytics problems</li>
<li>Standard methods are usually not enough to solve the business problems</li>
</ul>
</li>
<li>Too optimistic about data availability and quality
<ul>
<li>“Big Data” is not a guarantee of good and relevant data, usually big and messy</li>
<li>Unexpected efforts to bring the right data</li>
<li>Under estimate effort to evaluate quality of data</li>
</ul>
</li>
<li>Too optimistic about needed effort on data processing
<ul>
<li>Mismatch between different data sources</li>
<li>Table or column descriptions are not detailed enough</li>
<li>Lack in-depth understanding of the dataset or the domain</li>
<li>Under estimate of data preprocessing such as dealing missing data</li>
<li>Under estimate the effort for feature engineering</li>
</ul>
</li>
</ol>
<p><strong>Modeling Stage</strong></p>
<ol>
<li>Un-representative data such as lack of future outlook of what will happen in production or biased data</li>
<li>Too optimistic about model selection and hyper-parameter tuning to reach desired performance</li>
<li>Overfitting and obsession for complicated models (heavy models may leads poor production performance and maintenance)</li>
<li>Take too long to fail</li>
</ol>
<p><strong>Productionalization Stage</strong></p>
<ol>
<li>Bad production performance
<ul>
<li>Lack shadow mode dry run</li>
<li>Lack needed A/B testing</li>
<li>Data availability and stability issue in real time</li>
<li>Lack exception management on issues such as timeout and missing data</li>
</ul>
</li>
<li>Fail to scale in real time applications
<ul>
<li>Computation capacity limitation</li>
<li>Real time data storage and processing limitation</li>
<li>Latency constraints</li>
</ul>
</li>
</ol>
<p><strong>Post Production Stage</strong></p>
<ol>
<li>Missing necessary checkup
<ul>
<li>Lack model monitoring for key metrics</li>
<li>Lack exception notification</li>
<li>Lack model failures/timeout notification</li>
<li>Online feature not stored for future analysis</li>
</ul>
</li>
<li>Production performance degradation
<ul>
<li>Not aware of dynamic nature of the business problem</li>
<li>Not aware of changing input data quality and availability</li>
<li>Lack model tuning and re-training plan</li>
<li>Lack model retirement or replacement plan</li>
</ul>
</li>
</ol>
<h3 id="strategies-to-avoid-pitfalls">Strategies to Avoid Pitfalls</h3>
<ol>
<li>Be aware these pitfalls</li>
<li>Proactively discuss these pitfalls across teams</li>
<li>Be prepared when it happens</li>
<li>Have an end-to-end project cycle mindset</li>
<li>Ensure needed engineering resources available</li>
<li>True collaboration among teams</li>
</ol>
<h1 id="core-competencies">5 Core Competencies</h1>
<p>OCI provides 3 core components in AI/ML engineering to ensure the quality of the product as well as the maintainability of the product.</p>
<p><img src="https://lh3.googleusercontent.com/DxL7sk79Q6J8098M5Ewx-1Hu_rsRdI3B2wbLJa5xpxVQiodAw5Pfm9h94JnUFVBTtc5IeMoGTvlbB6BvmqYXBZtsBose1lJ_GSCB3uerKlgAViyEaR2UcHv37mTSIjVklvXAJIQB" alt=""></p>
<p>OCI also offer following advantages in soft skill</p>
<ol>
<li>Speed to solution
<ul>
<li>With help of an in house built AI solution platform called Alice AI, we can build the solution relatively quickly compared to other competitors.</li>
</ul>
</li>
<li>Value / Cost
<ul>
<li>We make sure every single model improvement means dollar values in your business.</li>
</ul>
</li>
<li>Philosophy of providing a solution (Value first)
<ul>
<li>If the model does not provide value in your business, we will be transparents about it.</li>
</ul>
</li>
<li>Leveraging other skills (Microservices) / Integrated
<ul>
<li>OCI offers other software solutions such as openDDS to provide the seamless integration into your existing platform.</li>
</ul>
</li>
</ol>
<p>OCI has already invested significant amount of resources and time to implement the some of the breakthrough ML technologies so that you do not have to pay for it such as</p>
<ul>
<li>Auto labelling</li>
<li>Auto QA/QC</li>
<li>Deep Learning Architectures</li>
<li>Auto Dashboard builder</li>
</ul>
<h2 id="other-competitors">Other Competitors</h2>
<p>We’ve summerized the core competitors across the US in ML space.<br>
Blue highlighted ones are OCI engaged projects.<br>
Count columnes represents the number of companies who are specialized in those services.<br>
<img src="https://lh6.googleusercontent.com/0zP3nZezFaGA5VgZXCALl_8VPET9ksLV2gfwwY4wwKPYVcUgrczwceHDsKnqX7sj28kP_0f729BF-c-Gw2Pwiaz0YlUJIk0vEqUt1fwZoTRBNCpntxKAhc5PsX7ZOkp7e8lStNEn" alt=""></p>
<p><img src="https://lh3.googleusercontent.com/ETALgbSG0ary0fopa0iBpg_q1pG_5ewp_kJihDf3LiHgbfwEScqE-WWJw_MergeNQJZNokVDTG8Wlg4df620O0d-hDTe4TVL_Sz5C1lmnO_sXBF2Wm0AEEsGwx_gQYBJ_G5_I2UG" alt=""></p>
<p><img src="https://lh5.googleusercontent.com/0ENJYUVCZyvwxxOX9GqYfebsBTiBkB2LIVigWTn5w7cr3lkzebQOioBu92UAJKDkf2FUg9HqivTXJjv-0Xof350Hxafdc7mK91TlYsr99xqs3uCO9RbGSE4U6jKrpL7TH3Gu1aMZ" alt=""></p>

