# EPTS Group GitHub Pages 部署说明

这个文件夹是给新仓库单独使用的版本，不会影响你之前 `Roventa Group` 的 GitHub 仓库。

## 上传哪些文件

只上传本文件夹里的：

- `index.html`

## 新仓库部署步骤

1. 在 GitHub 新建一个仓库，例如：`epts-protection-needs-quantifier`
2. 打开新仓库
3. 选择 `Add file` → `Upload files`
4. 把这个文件夹里的 `index.html` 上传到仓库根目录
5. 提交到 `main` 分支

## 开启 GitHub Pages

1. 进入新仓库的 `Settings`
2. 打开 `Pages`
3. 在 `Build and deployment` 里设置：
   - `Source`: `Deploy from a branch`
   - `Branch`: `main`
   - `Folder`: `/ (root)`
4. 保存
5. 等待几分钟

## 访问地址

成功后地址通常是：

`https://你的GitHub用户名.github.io/epts-protection-needs-quantifier/`

## 为什么不会影响旧仓库

因为 GitHub Pages 是按仓库分别部署的：

- 旧仓库继续保留原来的页面
- 新仓库只发布 `EPTS Group` 版本
- 两个仓库互不覆盖

## 注意

- 不要把旧仓库直接改名来替代新仓库
- 不要把旧仓库的远程地址覆盖成新仓库
- 最简单的方法就是：新建一个全新的仓库，只上传这个文件夹里的 `index.html`
