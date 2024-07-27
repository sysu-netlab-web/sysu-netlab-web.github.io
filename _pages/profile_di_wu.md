---
layout: profile
permalink: /team/diwu
redirect_from: /~dongsuh/
first_name: Di
last_name: Wu
title: Di Wi
subtitle: Ph.D.(CUHK), Professor, Associate Dean
profile: 
  image: profile/diwu.jpg
  address: "Sun Yat-sen University, Netlab <br>
            Building: NSCC-GZ, Office: 531 <br>
            Email: wudi27 (at)mail.sysu.edu.cn <br>"
---
<p class="profile-buttons">
    <a class="btn z-depth-0" href="http://netlabsysu.org/dwu/">CV</a>
    <a class="btn z-depth-0" href="https://scholar.google.com/citations?user=guhA4VoAAAAJ">Google Scholar</a>
    <a class="btn z-depth-0" href="wudi27@mail.sysu.edu.cn">Email</a>
</p>





**Di Wu** is a Professor and Associate Dean in the [School of Computer Science and Engineering](http://cse.sysu.edu.cn/), [Sun Yat-sen University](http://www.sysu.edu.cn/), Guangzhou, China. He received the B.S. degree from the [University of Science and Technology of China](http://www.ustc.edu.cn/en/), Hefei, China, in 2000; the M.S. degree from the [Institute of Computing Technology](http://www.ict.ac.cn/), Chinese Academy of Sciences, Beijing, China, in 2003; and the Ph.D. degree in Computer Science and Engineering from the [Chinese University of Hong Kong](http://www.cuhk.edu.hk/), Shatin, Hong Kong, in 2007. During 2007-2009, he worked as a postdoctoral researcher in the Department of Computer Science and Engineering, [NYU Polytechnic School of Engineering](http://engineering.nyu.edu/) (previously Polytechnic Institute of NYU), advised by [Prof. Keith W. Ross](https://engineering.nyu.edu/faculty/keith-ross). He was also working closely with [Prof. Yong Liu](http://engineering.nyu.edu/people/yong-liu) and Prof. Joel Wein. He was the co-recipient of IEEE INFOCOM 2009 Best Paper Award and IEEE Jack Neubauer Memorial Award, 2019.

He has served as the Media Streaming IG Chair (2014-present) of IEEE Communications Society Multimedia Communications Technical Committee, the Vice Chair of the 21th IEEE/ACM International Symposium on Cluster, Cloud and Internet Computing (CCGrid 2021), the TPC Co-chair of IEEE GLOBECOM-CCSNA Workshop 2014. He has also served as the Associate Editor of IEEE Transactions on Network Science and Engineering, the Guest Editor of IEEE Transactions on Circuits and Systems for Video Technology, and the Editor of a number of SCI-indexed journals, such as Springer Telecommunication Systems, Peer-to-Peer Networking and Applications, Security and Communication Networks, etc. His research interests include edge/cloud computing, distributed learning, multimedia networking, Internet measurement, and educational big data. He is a Distingished Member of CCF, a Senior Member of IEEE, and a Member of ACM and Sigma Xi.

### Research Projects
##### Distributed Infrastructure
 - Providing QoS in multi-tenant cloud environments through virtual network embedding
 - Enabling Distributed Optimization (Algorithms and Practice)
 - Scalable, high-performance networking stack, services, and applications

##### Distributed Intelligence
- Content-aware Internet video delivery using deep-learning \[[web page](http://web.inalab.net/~nas/)\]
- VDN: Enabling Software-defined, Near-Real Time Control for Content Delivery Networks
- Understanding the Internet video Quality of Experience (QoE) and QoE engineering
- Enhancing HTTP Adaptive Streaming with Network-level Predictions
- Reliable Real-time Communication on Content-aware Networks

##### Multimedia Networking
- Intel SGX \[[SGX reading list](https://docs.google.com/document/d/e/2PACX-1vQmwVAEA8p2BsCRoajcE4RKqwEmdReUZHavRePz4iN-2tdy_yQxGaO4oCfXmXlNmKry9GA3pgti6sYq/pub)\]
- OpenSGX: We recently released the \[[source code](https://github.com/sslab-gatech/opensgx)\] of an Intel SGX emulator!
- High-performance intrusion detection using many-core systems
- Automatic protocol and behavior analysis of Android Apps using binary analysis


### Students and Post-Docs
<ul>
{% assign skip_prof = false %}
{%- for group_mems in site.data.team -%}
    {% if skip_prof %}
        <li><b>{{group_mems[0]}}</b>: 
        {% assign members = group_mems[1] %}
        {% assign first = true %}
        {%- for member in members -%}
            {%- assign member_id = member.name | join: '_' | downcase -%}
            {%- assign member_homepage = "/team" | append: '#' | append: member_id -%}
            {%- if member.homepage -%}{%- assign member_homepage = member.homepage -%}{%- endif -%}
            {%- if first == false -%},{%- endif -%}{% assign first = false %} <a href="{{member_homepage}}">{{member.name | join: " "}}</a>
        {%- endfor -%}
        </li>
    {% endif %}
    {% assign skip_prof = true %}
{% endfor %}
</ul>

### Recent Publications
See [publications](/publications).

### Program Committee
- 2024: NSDI, SIGCOMM, CoNEXT, APNet, TheWebConf
- 2023: NSDI, APNet, CoNEXT PC
- 2022: SIGCOMM, NSDI, APNet, CoNEXT PC
- 2021: HotNets, ICNP, APNet
- 2020: USENIX ATC, ACM SIGCOMM, USENIX NSDI, ACM CoNEXT PC co-chair
- 2019: ACM SIGCOMM, ACM HotNets, ACM/IEEE Symposium on Edge Computing, ACM APNet (Co-chair), SysTEX
- 2018: USENIX NSDI, ACM HotNets, ACM APNet, ACM KBNets (Co-chair)
- 2017: ACM CoNEXT, ACM ANCS, ITC 29, APNet, APSys, KBNets, IEEE LANMAN, SysTEX workshop
- 2016: ACM CoNEXT, IEEE INFOCOM, ACM ANCS, IEEE LANMAN, ACM HotMiddlebox (Co-chair), ACM APSys
- 2015: IEEE ICNP, ACM HotMiddlebox, ACM ANCS, PAM, IEEE LANMAN
- 2014: IEEE LANMAN, ICCCN

### Services
- **Leadership**:
  - Chair of Interest Group on Media Streaming, IEEE Multimedia Communication Technical Committee (MMTC), 2014-present.
  - Vice Chair of the 21th IEEE/ACM International Symposium on Cluster, Cloud and Internet Computing (CCGrid 2021)
  - Track Chair, Software Defined Everything Track, International Conference on Cloud Computing and Big Data (CCBD 2015)
  - TPC Co-Chair, IEEE International Workshop on Cloud Computing Systems, Networks, and Applications (CCSNA), in conjunction with IEEE Global Communications Conference (GLOBECOM 2014)
  - Chair of CCF YOCSEF Guangzhou (2014-2015).

- **Editor Board**:
  - Associate Editor, IEEE Transactions on Network Science and Engineering (IEEE TNSE)
  - Guest Editor, IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT), Special Issue on “Visual Computing in the Cloud: Mobile Computing”, 2015.
  - Member of Editor Board, Telecommunication Systems, 2014-present.
  - Member of Editor Board, Peer-to-Peer Networking and Applications (PPNA), 2014-2016.
  - Member of Editor Board, Security and Communication Networks (SCN), 2014-2016.

- **TPC Member**:
  - 2020: IJCAI20, INFOCOM20
  - 2019: IEEE INFOCOM19, HotICN19, NPC19, TURC19
  - 2018: IEEE INFOCOM18, ACM Multimedia18, IEEE ICCCN18, NDCC18, ICC18, HotICN18
  - 2017: ACM Multimedia17, IFIP Networking17, IEEE ICC17 NGNI Symposium, IEEE ICNC17
  - 2016: IEEE ICC16, IEEE Globecom16, IEEE/CIC ICCC16, APCC16
  - 2015: IEEE ICC15, IEEE Globecom15, CCBD15, IEEE/CIC ICCC15
  - 2014: IEEE ICC14, IEEE Globecom14, IEEE NAS14, IEEE Workshop on Cloud Gaming at ICME14,
  - 2013: IFIP Networking13, IEEE ICC13, IEEE ICCCN13, IEEE Globecom13, IEEE ICCC13, SKG13
  - 2012: IEEE ICC12, IEEE CCNC12, IEEE Globecom12, GameNets12, NDCC12, FCST12, GPC12, PDCAT12
  - 2011: IEEE ICC11, IEEE AINA11, IEEE CCNC11 EDCN Workshop, PAKDD11, FCST11
  - 2010: IEEE ICCCN10, PAAP10
  - 2009: IEEE ICCCN09, PAKDD09, MUE09 P2P Video Streaming Workshop(PPVS09)
  - 2008: IEEE ICCCN08

- **Reviewer**:
  - Journals: IEEE/ACM Transactions on Networking, IEEE Journal on Selected Areas in Communications, IEEE Transactions on Computers, IEEE Transactions on Dependable and Secure Computing, IEEE Transactions on Information Forensics & Security, ACM Transactions on Multimedia Computing Communications and Applications, IEEE Transactions on Multimedia, IEEE Internet Computing, IEEE Network Magazine, Elsevier Computer Networks, Elsevier Journal of Parallel and Distributed Computing, Elsevier Journal of Performance Evaluation, etc.
  - Conferences: IJCAI, ACM SIGMETRICS, IEEE Infocom, ICDCS, IFIP Networking, IEEE ICC, IEEE Globecom, IEEE LCN, IEEE ICCCN, IPTPS, PAKDD, IEEE P2P, etc. Membership: ACM, IEEE, IEEE Computer Society, Sigma Xi, CCF

### Teaching
- **Lecturer, Sun Yat-Sen University**
  - Principle and Practice of Super-computers, Spring 2019, Spring 2020, Spring 2021.
  - Fundamentals of High-Performance Computing, Fall 2019, Fall 2020, Fall 2021.
  - Cloud Computing, Spring 2017.
  - Cloud Data Management, Fall 2016.
  - Advanced Topics on Computer Networking, Spring 2011.
  - Computer Organizatoin, Spring 2011, Spring 2012, Spring 2013, Fall 2013, Summer 2014, Summer 2015
  - Computer Networking, Fall 2010, Spring 2015, Spring 2016, Fall 2017, Fall 2018.
  - Network Security, Spring 2010, Fall 2011, Fall 2012, Spring 2014

- **Guest Lecturer/Teaching Assistant, Polytechnic Institute of NYU**
  - CSC684 Computer Networking, Fall 2007, Spring 2008, Fall 2008
  - CSC682 Computer Security, Spring 2008, Spring 2009

- **Teaching Assistant, Chinese University of Hong Kong**
  - CSC4430 Data Communication and Computer Networks, Spring 2007
  - CSC3160 Design and Analysis of Algorithms, Fall 2006
  - CSC3180 Principles of Programming Languages, Spring 2006
  - CSC5110 Advanced Software Engineering, Fall 2005
  - CSC2100A Data Structures, Fall 2005
