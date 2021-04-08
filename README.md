# edx_course_templater

页面[web page](https://haharay.github.io/edx_course_templater/index.html) 在tarball文件中生成edX课程结构，可以立即将其导入到EdX Studio中。 您填写表格以描述您的课程，选择一些内容，例如各个章节部分的数量，是否包含视频/文本/问题，首页/末页是否不同等。该课程包含在带有标准介绍的样板课程中和包装材料。

与往常一样，这些内容将覆盖您现有的课程，因此不要将它们导入已经完成工作的课程之上。 取而代之的是，在您的过程的早期使用此方法，以节省您构建数百个空白组件的繁琐工作。

所有这些都在客户端运行。 不需要服务器。

Pro Notes:

- Ready for use in production. Version 1.0.0
- We're using [TarballJS](https://github.com/ankitrohatgi/tarballjs) to make tar files, and [vkbeautify](https://github.com/vkiryukhin/vkBeautify) to pretty-print. Both are MIT-licensed. Snapshots of them are included in this repo.
- You can point this at your own boilerplate course if you want. You'll need an index file. Download and unzip your course, and run `find path/to/folder -type f > course_structure.txt` to create a flat file that describes the course structure. Here's [our boilerplate structure](https://github.com/HarvardX/edx_course_templater/blob/master/boilerplate_course.txt) if you want an example of what yours should look like.

Written by Colin Fredericks for HarvardX.
Last code update: November 20th, 2019.
Last update to boilerplate course: January 4th, 2021
