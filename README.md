<div align="center">

<!-- ====================================================== -->
<!--       南 昌 大 学 · 个人课程作品集主仓库                  -->
<!--       Nanchang University · Course Portfolio            -->
<!-- ====================================================== -->

<img src="https://img.shields.io/badge/School-南昌大学(NCU)-C8102E?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJsMyA3aDd2N2wtLTUgNSAyIDctNy00LTctNyA0IDUtMi01LTctN3YtMmwxMC0xMHoiIGZpbGw9IiNmZmYiLz48L3N2Zz4=" />
<img src="https://img.shields.io/badge/Role-Personal%20Portfolio-FFD700?style=for-the-badge" />
<img src="https://img.shields.io/badge/Course-2026%20Fall-2E8B57?style=for-the-badge" />
<img src="https://img.shields.io/badge/Weeks-16-4682B4?style=for-the-badge" />

> **"格物致新，厚德泽人" —— 记录每一步成长**

</div>

---

## 一、个人信息卡 (Student Info)

| 字段       | 内容                                                                 |
| ---------- | -------------------------------------------------------------------- |
| **学校**   | 🏛️ 南昌大学 (Nanchang University)                                  |
| **学院**   | _(待填)_                                                              |
| **学号**   | `6601126059`                                                       |
| **姓名**   | 傅倩                                                                 |
| **专业**   | 护理学                                                                |
| **入学年份** | 2026                                                                |
| **GitHub** | 🔗 _(待填)_                                                          |
| **邮箱**   | _(待填)_                                                              |

> ✅ **信息已登记**：傅倩 / 6601126059 / 护理学。需要修改时直接编辑本文件，然后 `git add` + `git commit` + `git push`。

---

## 二、本学期 16 周实验目录树 (16-Week Labs)

本仓库按教学周次组织实验内容与作业。每个子目录对应一周的实验材料。

```text
.
├── README.md                 ← 你正在阅读的文件 (本文件)
├── .gitignore                ← 告诉 Git 哪些文件不要追踪
│
├── Week-01/                  ← 第 01 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-02/                  ← 第 02 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-03/                  ← 第 03 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-04/                  ← 第 04 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-05/                  ← 第 05 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-06/                  ← 第 06 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-07/                  ← 第 07 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-08/                  ← 第 08 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-09/                  ← 第 09 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-10/                  ← 第 10 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-11/                  ← 第 11 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-12/                  ← 第 12 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-13/                  ← 第 13 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-14/                  ← 第 14 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
├── Week-15/                  ← 第 15 周 实验材料
│   ├── 实验报告.md
│   └── 源代码/
│
└── Week-16/                  ← 第 16 周 (期末) 实验材料
    ├── 实验报告.md
    └── 源代码/
```

---

## 三、使用方法 (How to Use)

### 🆕 新增某一周实验
```bash
# 例：上传第 3 周作业
mkdir Week-03/源代码
echo "print('Hello World')" > Week-03/源代码/hello.py
git add Week-03/
git commit -m "Week-03: 提交第 3 周实验代码"
git push
```

### 📝 修改个人信息
1. 在仓库根目录找到 `README.md`
2. 修改个人信息卡里的学号 / 姓名 / 专业（`Week-01` ~ `Week-16` 实验报告模板中的同名信息已同步）
3. 重新 `git add` + `git commit` + `git push`

### 💡 常用 Git 命令速查
| 命令 | 作用 |
|------|------|
| `git status` | 看哪些文件被修改了 |
| `git add 文件名` | 把文件放进"待提交"篮子里 |
| `git commit -m "说明"` | 给这批改动盖个"日期章" |
| `git push` | 把本地改动送到 GitHub 云端 |
| `git pull` | 把 GitHub 云端最新内容拉回本地 |

---

## 四、版权与许可 (License)

本仓库采用 **MIT License** 开源（你也可以换成学校要求的格式）。

```
MIT License

Copyright (c) 2026 傅倩 · NCU

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software...
```

---

## 五、致谢 (Acknowledgements)

- 🏫 感谢南昌大学的培养
- 👨‍🏫 感谢任课教师的指导
- 🌟 感谢 GitHub 提供这么好的免费平台

---

<div align="center">
<sub>📌 本仓库由结对工程顾问协助自动初始化 · 2026 年 10 月</sub>
</div>
