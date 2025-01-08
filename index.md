---
layout: default
title: Home
---

<style>
    /* Responsive adjustments */
    .profile-section {
        display: flex;
        flex-direction: row;
        align-items: flex-start;
        gap: 2rem;
        text-align: left;
    }
    .profile-text {
        flex: 2;
    }
    .profile-image {
        flex: 1;
    }
    .profile-image img {
        max-width: 100%;
        height: auto;
        border-radius: 5px;
    }

    /* Font size adjustments */
    h1 span {
        font-size: 1.5rem;
    }
    h2, h3, h4, h5, h6 {
        font-size: 1.2rem;
    }
    #recent-news {
        font-size: 1.2rem;
    }

    /* Content container */
    .content-wrapper {
        position: relative;
        padding-top: 0.5rem;
    }

    /* Responsive layout for mobile */
    @media (max-width: 768px) {
        .profile-section {
            flex-direction: column;
        }
        .profile-image {
            order: -1;
        }
    }
</style>

<div class="content-wrapper">
    <div class="lang-switch">
        <a href="/cn/">中文</a>
    </div>

    <h1><span style="color: #2c3e50; font-size: 1.5rem;">Ning Xie (谢宁)</span></h1>

    <div class="profile-section">
        <div class="profile-text">
            I am a <span style="color: #2c3e50; font-weight: 600;">Research Scientist</span> at the <a href="https://www.med.upenn.edu/genetics/" target="_blank">University of Pennsylvania</a>. My research focuses on understanding the <span style="color: #2c3e50; font-weight: 600;">genetic and molecular mechanisms underlying cardiovascular and skeletal muscular diseases</span>, with particular emphasis on the role of <span style="color: #2c3e50; font-weight: 600;">non-coding variants</span> in these conditions.

            With expertise in <span style="color: #2c3e50; font-weight: 600;">stem cell biology, single-cell techniques, CRISPR editing, and mouse modeling</span>, I have developed an integrative approach that utilizes cutting-edge technologies to efficiently identify functional mutations and their target genes, contributing novel insights into the molecular mechanisms of these diseases.

            Before joining UPenn, I received my PhD in Molecular Medicine from <a href="https://www.pku.edu.cn/" target="_blank">Peking University</a> (2015) and BS in Biology from <a href="https://www.scu.edu.cn/" target="_blank">Sichuan University</a> (2010).

            <div style="margin-top: 1.5rem;">
            <span style="color: #2c3e50; font-weight: 600;">Research Highlights:</span>
            <ul style="list-style-type: none; padding-left: 0; margin-top: 0.5rem;">
                <li style="margin-bottom: 0.5rem;">• Received the Reviewers’ Choice Abstracts Award at  ASHG 2022</li>
                <li style="margin-bottom: 0.5rem;">• Awarded the 35th Annual PRESS Award at the University of Minnesota, USA</li>
                <li style="margin-bottom: 0.5rem;">• Published in Stem Cell Reports on skeletal muscle regeneration</li>
            </ul>
            </div>
        </div>
        <div class="profile-image">
            <img src="assets/images/photo1.jpg" alt="Ning Xie">
        </div>
    </div>

    <h2><span style="color: #2c3e50; font-weight: 600;" id="recent-news">Recent News</span></h2>
    {% include news_list.html limit=3 show_more=true %}
</div>