## Hexo Theme Setup and Customization
- **Theme**: [Frame](https://github.com/zoeingwingkei/frame/) 
- **Search**: Integrated `local_search` with custom `Ctrl+K` shortcut.
- **Comments**: Using `Utterances` with GitHub Issues as the comment system.
- **Table of Contents**: Added `hexo-toc` for article navigation with anchor links.
- **Tags**: Chinese tags for series, English tags for general use.
- **Header**: Sticky with a glassmorphism effect; replaced the text-based search button with a magnifying glass icon and customized the fonts.
- **Google Analytics**
- **Custom CSS**: Multiple style tweaks across the blog.

## Reference
- **Comments:**
  - **Murmuring**: `Frame` theme supports `Valine` and `Disqus` comment systems, both of which I tried. However, each had issues that I didn't like, and they added extra complexity with third-party management. I ultimately chose Utterances, even though it requires GitHub login, which limits access for non-developer users.
  - **Disqus:** Too bulky and honestly, just not visually appealing. Check out [Disqus](https://disqus.com/) here.
  - **Valine**: Work with LeanCloud for storage, it has a fine style, but I encountered issues with the comment feature not working on the international version. Although this could be fixed, I switched to Utterances for its clean, GitHub-style simplicity. Check out [Valine](https://valine.js.org/) here.
  - **utterances:** Check the official documentation for [utterances](https://utteranc.es/) here, and for a reference in Chinese, see [Hexo 新增 utterances 留言板與方案選擇思路](https://blog.kyomind.tw/hexo-blog-reply/).
- **Table of Contents:**
  - [hexo-toc repo](https://github.com/bubkoo/hexo-toc)  
  - Later discovered `Hexo` provides [toc helpers](https://hexo.io/zh-tw/docs/helpers.html#toc) natively.
- **Google Search Console:** [SEO 優化 (一)：為什麼搜尋 (Google) 不到我的 Hexo 部落格？](https://jenifers001d.github.io/2019/12/09/SEO/SEO1-Website-is-Not-Showing-in-Google-Search/)
- **Google Analytics Setup:** [Day 12：為 Hexo 裝設 Google Analytics，追蹤你的部落格流量（使用 Next 佈景主題）](https://ithelp.ithome.com.tw/m/articles/10272965)