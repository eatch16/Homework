<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>陈雨桐博士 - 学术简历</title>
    <style>
        :root {
            --bg-about: #F3F6F9;
            --bg-education: #F9F3F6;
            --bg-awards: #F6F9F3;
            --bg-contact: #EFF3F7;
        }

        body {
            font-family: '微软雅黑', system-ui, sans-serif;
            line-height: 1.6;
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .section {
            padding: 2rem;
            border-radius: 15px;
            margin-bottom: 2.5rem;
            box-shadow: 0 5px 15px rgba(0,0,0,0.08);
            transition: transform 0.3s ease;
        }

        .section:hover {
            transform: translateY(-3px);
        }

        .about { background: var(--bg-about); border-left: 5px solid #7AA3CC; }
        .education { background: var(--bg-education); border-left: 5px solid #CC7AA3; }
        .awards { background: var(--bg-awards); border-left: 5px solid #A3CC7A; }
        .contact { background: var(--bg-contact); border-left: 5px solid #7AA3CC; }

        h1 {
            color: #2B394E;
            font-size: 2.8rem;
            margin-bottom: 0.8rem;
        }

        .profile-header {
            display: grid;
            grid-template-columns: auto 1fr;
            gap: 3rem;
            align-items: center;
            margin-bottom: 3rem;
        }

        .profile-photo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            box-shadow: 0 8px 20px rgba(0,0,0,0.15);
        }

        .timeline {
            position: relative;
            padding-left: 30px;
        }

        .timeline::before {
            content: '';
            position: absolute;
            left: 0;
            top: 10px;
            bottom: 10px;
            width: 3px;
            background: linear-gradient(to bottom, #7AA3CC, #A3CC7A);
        }

        .timeline-item {
            position: relative;
            padding: 2rem;
            margin-bottom: 2rem;
            background: rgba(255,255,255,0.95);
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.05);
        }
    </style>
</head>
<body>
    <div class="profile-header">
        <img src="https://via.placeholder.com/150" alt="陈雨桐" class="profile-photo">
        <div>
            <h1>陈雨桐 博士</h1>
            <p style="font-size: 1.2rem; color: #4A5C6E;">人工智能与医疗影像分析专家</p>
            <p style="color: #6B7C8F;">上海交通大学计算机科学与技术博士（2025届）</p>
        </div>
    </div>

    <div class="section about">
        <h2>个人简介</h2>
        <p>专注于医学影像的深度学习算法研究，在《Medical Image Analysis》《IEEE TMI》等期刊发表论文15篇。开发的肝脏肿瘤自动分割系统在MICCAI挑战赛中取得top 5%成绩。</p>
        
        <h3>核心能力</h3>
        <ul>
            <li>医学影像处理（CT/MRI/X-ray）</li>
            <li>深度学习框架（PyTorch/TensorFlow）</li>
            <li>3D图像重建与可视化</li>
            <li>多模态数据融合</li>
        </ul>
    </div>

    <div class="section education">
        <h2>教育经历</h2>
        <div class="timeline">
            <div class="timeline-item">
                <h3>上海交通大学 · 计算机科学与技术博士</h3>
                <p>2020-2025 | GPA 3.95/4.0</p>
                <ul>
                    <li>导师：王立军教授（国家杰出青年科学基金获得者）</li>
                    <li>研究方向：基于深度学习的肝癌早期诊断</li>
                    <li>华为奖学金获得者（2023）</li>
                </ul>
            </div>

            <div class="timeline-item">
                <h3>浙江大学 · 生物医学工程学士</h3>
                <p>2016-2020 | GPA 3.9/4.0</p>
                <ul>
                    <li>竺可桢奖学金（全校前1%）</li>
                    <li>全国大学生生物医学工程创新设计大赛特等奖</li>
                </ul>
            </div>
        </div>
    </div>

    <div class="section awards">
        <h2>荣誉奖项</h2>
        <div class="timeline">
            <div class="timeline-item">
                <h3>2024年吴文俊人工智能优秀青年奖</h3>
                <p>人工智能领域35岁以下青年学者最高荣誉</p>
            </div>

            <div class="timeline-item">
                <h3>2023年MICCAI Liver Tumor Segmentation冠军</h3>
                <p>Dice系数达到0.923（专家标注水平0.89-0.91）</p>
            </div>
        </div>
    </div>

    <div class="section contact">
        <h2>联系方式</h2>
        <ul>
            <li>📧 yutong.chen@sjtu.edu.cn</li>
            <li>📱 +86 139-8765-4321</li>
            <li>📍 上海市徐汇区上海交通大学闵行校区</li>
            <li>GitHub: @YutongMedAI</li>
        </ul>
    </div>
</body>
</html>
