# The difference between Sql server and Oracle
<style>
    table th:first-of-type {
        width: 50px;
        background:grey;
    }
    table th:nth-of-type(2) {
        width: 200pt;
    }
    table th:nth-of-type(3) {
        width: 200pt;
    }

    table th:nth-of-type(3) {
        width: 200pt;
    }
        table td:first-of-type {
        background:grey;
    }
</style>
不同点 |Sql server | Oracle
---|------|---
基础语法 | @ 表示局部变量<br>@@ 表示系统变量 | 不能使用@@ 和@，复制语句需要使用 变量:= 值（表达式）<br>定义变量： DELLARE 变量1 类型
IF...ELSE | IF(TRUE)<BR>&emsp;BEGIN<BR>....<BR>END<BR>ELSE<BR>&emsp;BEGIN<BR>....<BR>END | IF(TRUE) THEN <BR>....<BR>ELSE<BR>....<br>END IF;


