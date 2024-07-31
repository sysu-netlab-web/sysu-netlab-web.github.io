---
layout: about
title: About
permalink: /
redirect_from: /new_home/
subtitle: 
news: true  # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---
<style>
    p {
        line-height: 1.6em;
    }
</style>


<div class="row justify-content-sm-center">
    <div class="col-md mt-3 col-md-12">
        {% include figuren.html path="/assets/img/main/lab1.jpg" title="Lab members" alt="Lab members" class="img-fluid rounded z-depth-1 main-image-1" %}
        <div class="caption">
        </div>
    </div>
</div>

## **NetLab**

Welcome to **NetLab**[@SYSU](https://www.sysu.edu.cn/)! 

<div class="mt-4 mb-5 pt-4 pl-4 pr-4 pb-2" style="background:var(--global-code-bg-color); position: relative;" id="prof-word-zh">
    <div style="position: absolute; top: 1.5em; right: 1.5em;">
        <a href="javascript:switchTo('zh')" style="opacity: 50%">🇨🇳</a>&nbsp;
        <a href="javascript:switchTo('en')">🇺🇸</a>
    </div>
    &nbsp;
    <div id="content-zh">
        <p>INA研究组致力于互联网服务与应用、云基础设施以及支持人工智能的系统中的创新理念。我们识别并预见了因互联网/云服务的发展和新硬件的出现而带来的新问题，为现实世界中的挑战性问题提供了新颖的解决方案，并以实现实际影响的方式设计和实施这些解决方案。INA研究组是[电子工程学院](https://ee.kaist.ac.kr)的[计算机系](https://computer.kaist.ac.kr)的一部分。</p>
    
        <p>INA研究组提供一个自我激励的氛围，通过灵活的工作时间实现高效的研究。在博士项目中，我们的研究组提供必要的培训，使学生成为独立研究者，并成为特定领域的专家。我们还与国外研究人员进行积极交流，实验室的校友在毕业后拥有强大的网络，并在进入行业、研究实验室或学术界时获得许多机会。</p>
    
        <p>开放职位： 我们正在寻找研究生和本科研究实习生加入INA实验室（常年招聘）。我们有几个有趣的研究主题，如大规模深度学习、神经体积流和回顾性视频分析。您可以在[Join Us](/join-us)页面找到更多信息。</p>
    </div>
</div>

<div class="mt-4 mb-5 pt-4 pl-4 pr-4 pb-2" style="background:var(--global-code-bg-color); position: relative;" id="prof-word-en">
    <div style="position: absolute; top: 1.5em; right: 1.5em;">
        <a href="javascript:switchTo('zh')">🇨🇳</a>&nbsp;
        <a href="javascript:switchTo('en')" style="opacity: 50%">🇺🇸</a>
    </div>
    &nbsp;
    <div id="content-en">
        <p> INA research group pursues innovative ideas in/for Internet services and applications, cloud infrastructure, and systems that support artificial intelligence. We identify and anticipate new problems that arise from the evolution of Internet-/Cloud-based services and the development of new hardware, provide novel solutions for challenging problems in the real-world, design and implement the solutions in a way that reaches out for real-world impact. INA research group is part of the [Computer Division](https://computer.kaist.ac.kr) of the [School of Electrical Engineering](https://ee.kaist.ac.kr).</p>

        <p> INA research group provides a self-motivated atmosphere that allows for efficient research through flexible working hours. In the doctoral program, our research group provides the necessary training to become an independent researcher and become an expert in a particular field. There is also active exchange with foreign researchers, and Lab alumni have a strong network and receive many offers upon graduation, entering the industry, research lab, or academia as illustrated in [Alumni@INA](/alumni).</p>

        <p> Open Position: We are looking for graduate students and undergraduate research interns to join the INA lab. We have several interesting topics such as large-scale deep learning, neural volumetric streaming, and retrospective video analytics. You can find more information on [Join Us](/join-us) page.</p>
    </div>
</div>

<script>
    function isChinese() {
        return (window.navigator.userLanguage || window.navigator.language || '').startsWith('zh');
    }
    function switchTo(lang) {
        if (lang === 'zh') {
            document.getElementById('prof-word-zh').style.display = 'block';
            document.getElementById('prof-word-en').style.display = 'none';
        } else {
            document.getElementById('prof-word-en').style.display = 'block';
            document.getElementById('prof-word-zh').style.display = 'none';
        }
    }

    if (isChinese()) {
        switchTo('zh');
    } else {
        switchTo('en');
    }
</script>

&nbsp;
&nbsp;
## **Research**

INA has published 14 papers at top-tier systems conferences, **ranking 1st in Korea** (refer to [link](https://csrankings.org/#/index?comm&kr)).
Currently, INA Lab is conducting research in three different directions, which are listed below. You can find a full list of projects and publications on [Project@INA](/projects) and [Publication@INA](/publications).

#### _<i class="fa fa-robot mr-2 mt-3"></i>_  **Systems for AI and Cloud**
- Accelerating training for large-scale deep neural networks [[ICML'22](/projects/tspipe), ICML'24, SIGCOMM'24]
- Accelerating DNA sequencing by learned index [[Bioinformatics'22](/projects/bwa-meme)]
- Optimizing microservice auto-scaling by graph neural networks [[CoNEXT'21](/projects/graf), SIGCOMM'24]
- Optimizing systems for LLM training and inference

#### _<i class="fa fa-photo-video mr-2"></i>_ **AI-augmented Media Delivery**
<!-- - Improving video streaming quality by neural super-resolution -->
- Incorporating neural enhancement with adaptive video streaming [[OSDI'18](/projects/nas), [SIGCOMM'20](/projects/livenas)]
- Accelerating neural enhancement at scale [[MobiCom'20](/projects/nemo/), [SIGCOMM'22](/projects/neuroscaler)]
- Optimizing traditional image codecs for neural enhancement [[CVPR'23](/projects/accelir)]

#### _<i class="fa fa-cloud mr-2"></i>_  **Networked Systems (Data center, 5G) / Systems Security**
- Integrating trusted execution environment with conventional networked systems [[NSDI'17,ToN'20,ToN'22](/projects/sgx)]
- Optimizing network resource and wireless spectral efficiency under 5G, 6G environments [[CoNEXT'22](/projects/outran)]
- Improving congestion control schemes for datacenter networking [[SIGCOMM'17](/projects/expresspass), [EuroSys'21](/projects/tlt), [EuroSys'23](/projects/flexpass)]

&nbsp;
&nbsp;
&nbsp;
