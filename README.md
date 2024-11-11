# Book Recommendation Repository

Welcome to the Book Recommendation Repository! This repository provides book recommendations in both Chinese and English. Use the buttons below to toggle between languages.

---

## Language Toggle
<button onclick="switchLanguage('english')">English</button>
<button onclick="switchLanguage('chinese')">中文</button>

<script>
function switchLanguage(language) {
    const englishSections = document.querySelectorAll('.english');
    const chineseSections = document.querySelectorAll('.chinese');

    if (language === 'english') {
        englishSections.forEach(section => section.style.display = 'block');
        chineseSections.forEach(section => section.style.display = 'none');
    } else {
        englishSections.forEach(section => section.style.display = 'none');
        chineseSections.forEach(section => section.style.display = 'block');
    }
}
</script>

---

## Book Recommendations

<div class="english" style="display: block;">
**Book Title:** To Kill a Mockingbird  
**Author:** Harper Lee  
**Description:** A classic novel exploring themes of racial injustice and moral growth.
</div>

<div class="chinese" style="display: none;">
**书名：** 杀死一只知更鸟  
**作者：** 哈珀·李  
**简介：** 这是一部经典小说，探讨了种族不公正与道德成长的主题。
</div>

---

## How to Contribute

<div class="english" style="display: block;">
1. Fork this repository.
2. Create a new branch for your recommendations.
3. Submit a pull request with your recommended books.
</div>

<div class="chinese" style="display: none;">
1. Fork 本仓库。
2. 为您的推荐创建一个新分支。
3. 提交包含推荐书籍的 pull request。
</div>

---

## Resources

This feature will work best if deployed on GitHub Pages or a static site that renders JavaScript.
