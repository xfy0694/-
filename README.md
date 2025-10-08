# -
[index.html](https://github.com/user-attachments/files/22761005/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PDCdb - 化合物信息</title>
  <link rel="stylesheet" href="index.css" />
  <style>
    /* 搜索提示样式，可放进 index.css */
    .search-info {
      text-align: center;
      margin: 30px auto 20px;
      line-height: 1.5;
      color: #1d4e89;
    }
    .search-info h2 {
      font-size: 22px;
      font-weight: 600;
      color: #1e40af;
      margin: 0 0 6px;
    }
    .search-info span {
      color: #2563eb;
      font-weight: 500;
    }
    .search-info p {
      margin: 0;
      font-size: 15px;
      color: #334155;
    }
  </style>
</head>

<body>
  <!-- 顶部标题 -->
  <header>
    <img src="https://www.rcsb.org/static/images/icons/protein.png" alt="PDCdb Logo" />
    <h1>PDCdb - Pharmaceutical & Biological Data</h1>
  </header>

  <!-- 居中导航 -->
  <nav>
    <a href="#">Home</a>
    <a href="#">Search</a>
    <a href="#">Download</a>
    <a href="#">About</a>
    <a href="#">Help</a>
  </nav>

  <!-- 主体内容 -->
  <main>

    <!-- ✅ 新增：搜索提示区 -->
    <section class="search-info">
      <h2>Search for <span>XX</span></h2>
      <p>You are searching for: <span>“XX”</span></p>
    </section>

    <!-- 原化合物信息表格 -->
    <table class="compound-table">
      <colgroup>
        <col class="col-label">
        <col class="col-value">
      </colgroup>

      <tr class="table-title">
        <th colspan="2">化合物ID： XX</th>
      </tr>

      <tr><td class="label">名称</td><td></td></tr>
      <tr class="row-structure"><td class="label">结构图</td><td></td></tr>
      <tr><td class="label">靶点</td><td></td></tr>
      <tr><td class="label">同位素</td><td></td></tr>
      <tr><td class="label">探针类型</td><td></td></tr>
      <tr><td class="label">尿液半衰期</td><td></td></tr>
      <tr><td class="label">血浆半衰期</td><td></td></tr>
      <tr><td class="label">肿瘤摄取值</td><td></td></tr>
      <tr><td class="label">文献链接</td><td></td></tr>
      <tr><td class="label">临床试验阶段</td><td></td></tr>
    </table>

  </main>
</body>
</html>
