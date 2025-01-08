---
layout: default
title: 主页
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

    /* Content container */
    .content-wrapper {
        position: relative;
        padding-top: 1rem;    

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
        <a href="/">English</a>
    </div>

    <h1><span style="color: #2c3e50; font-size: 1.5rem;">谢宁</span></h1>

    <div class="profile-section">
        <div class="profile-text">
            我是<a href="https://www.med.upenn.edu/genetics/" target="_blank">宾夕法尼亚大学</a>的<span style="color: #2c3e50; font-weight: 600;">研究科学家</span>。我的研究主要关注<span style="color: #2c3e50; font-weight: 600;">心脏发育和疾病的遗传调控变异</span>，特别是<span style="color: #2c3e50; font-weight: 600;">非编码变异</span>在心血管疾病中的作用。

            我在<span style="color: #2c3e50; font-weight: 600;">心脏发育和疾病的遗传调控变异</span>方面具有专业知识，开发了整合性方法，利用前沿技术包括<a href="https://genomebiology.biomedcentral.com/articles/10.1186/s13059-023-02856-6" target="_blank">GWAS</a>、<a href="https://www.nature.com/articles/s41576-023-00583-z" target="_blank">单细胞RNA测序</a>和<a href="https://www.synthego.com/learn/crispr" target="_blank">CRISPR基因编辑</a>来高效识别功能性突变及其靶基因，为理解心血管疾病的分子机制提供新见解。

            在加入宾大之前，我分别于2015年和2010年获得<a href="https://www.pku.edu.cn/" target="_blank">北京大学</a>分子医学博士学位和<a href="https://www.scu.edu.cn/" target="_blank">四川大学</a>生物学学士学位。

            <div style="margin-top: 1.5rem;">
            <span style="color: #2c3e50; font-weight: 600;">荣誉和文章：</span>
            <ul style="list-style-type: none; padding-left: 0; margin-top: 0.5rem;">
                <li style="margin-bottom: 0.5rem;">• 获得ASHG 2022年会的审稿人选择摘要奖</li>
                <li style="margin-bottom: 0.5rem;">• 获得美国明尼苏达大学第35届年度PRESS奖</li>
                <li style="margin-bottom: 0.5rem;">• 在《Stem Cell Reports》上发表关于骨骼肌源性祖细胞高移植能力的研究</li>
            </ul>
            </div>
        </div>
        <div class="profile-image">
            <img src="../assets/images/photo1.jpg" alt="谢宁">
        </div>
    </div>
</div> 