
自动化管理
=============================


一、作业管理
````````````````````````

::

    点击左侧菜单“自动化管理”下的“作业管理菜单”

.. image:: ../_static/img/using/job/1.jpg

::

    点击上方的内容筛选框，可以根据模糊搜索、模板、主机清单、凭据进行查询并返回结果，也可以点击旁边的高级筛选条件进行搜索查询。

.. image:: ../_static/img/using/job/2.jpg

::

    点击操作框内的日志查看按钮

.. image:: ../_static/img/using/job/5.jpg

::

    跳转到该作业的日志页面、左边部分显示该作业的信息、右边部分显示日志信息

.. image:: ../_static/img/using/job/6.jpg

::

    点击操作框内的执行按钮

.. image:: ../_static/img/using/job/7.jpg

::

    提示确认信息，确认后执行命令,跳转到该作业的日志页面

.. image:: ../_static/img/using/job/8.jpg

.. image:: ../_static/img/using/job/9.jpg

::

    点击操作框内的删除按钮，可以删除当前行数据

.. image:: ../_static/img/using/job/10.jpg

::

    提示确认信息，确认后进行数据删除

.. image:: ../_static/img/using/job/11.jpg

.. image:: ../_static/img/using/job/12.jpg

::

    点击右上角的列显示状态按钮下拉菜单，并点击要隐藏或者展示的列来获取相应列的信息

.. image:: ../_static/img/using/job/13.jpg

.. image:: ../_static/img/using/job/14.jpg


::

    选择一个模板的作业类型为工作流的作业，点击执行按钮，跳转到工作流图形页面
    展示该工作流模板的流程图下的各个节点运行状态，可以根据右侧的状态信息进行了解


.. image:: ../_static/img/using/job/15.png


::

    在展示的流程图形页面可以点击节点上的查看按钮，会跳转到该节点下的模板任务执行情况


.. image:: ../_static/img/using/job/16.png

.. image:: ../_static/img/using/job/17.jpg

::

    模板类型为工作流的模板可以点击前面的加号，会展示出该ID下的子作业数据。

.. image:: ../_static/img/using/job/18.jpg

.. image:: ../_static/img/using/job/19.jpg

::

    同时可以对子作业进行执行、查看、删除等操作，功能与前面所介绍的类似。

::

    说明：1、当作业类型为自动化作业或者命令，点击执行按钮跳转到作业日志页面
          2、当作业类型为工作流，点击执行按钮跳转到工作流程图形页面
          对应页面如下如：

.. image:: ../_static/img/using/job/20.png

.. image:: ../_static/img/using/job/21.png

.. image:: ../_static/img/using/job/22.png

.. image:: ../_static/img/using/job/23.png



二、快速命令
````````````````````````

::

    点击左侧菜单“自动化管理”下的“快速命令菜单”

.. image:: ../_static/img/using/job/25.png

::

    添加相应的数据(像模块、登录凭据(ssh)、主机清单等下拉框值均要在相应的页面进行新增数据才可显示)具体情况如下图：

::

    点击左侧菜单“系统管理”下的“Ansible模块”、在此页面进行新增需要的模块。

.. image:: ../_static/img/using/job/24.png


::

    点击左侧菜单“资源管理”下的“凭据管理”、在此页面进行新增需要的凭据。

.. image:: ../_static/img/using/job/26.png


::

    点击左侧菜单“资源管理”下的“主机清单”、在此页面进行新增需要的主机清单（详细步骤已在介绍主机清单说明）。

.. image:: ../_static/img/using/job/27.png


::

    最后添加数据，并点击右上角的执行命令按钮，页面进行跳转。

.. image:: ../_static/img/using/job/28.png


::

    该批量命令会跳转到该任务的日志页面，展示该批量命令运行的信息

.. image:: ../_static/img/using/job/29.png


三、Playbook执行
````````````````````````

::

   点击左侧菜单“自动化管理”下的“Playbook执行”

.. image:: ../_static/img/using/job/30.png

::

   填写或选择相应的数据（像主机清单、登录凭据(ssh)上面以作叙述，这里不再介绍）
   这里介绍如何获取tags和skip_tags、点击左侧菜单“系统管理”下的“Playbook tag”

.. image:: ../_static/img/using/job/31.png


::

   最后填写具体数据，并点击右上角的执行按钮

.. image:: ../_static/img/using/job/32.png

::

   该作业会跳转到相应的日志页面，并展示该作业运行的具体信息以及日志信息

.. image:: ../_static/img/using/job/33.png


四、计划任务
````````````````````````

::

   点击左侧菜单“自动化管理”下的“计划任务菜单”

.. image:: ../_static/img/using/job/34.png

::

   点击页面上的新增按钮,执行方式为计划任务

.. image:: ../_static/img/using/job/35.png

::

   点击新增按钮,执行方式为固定间隔

.. image:: ../_static/img/using/job/36.png

::

   点击新增按钮,执行方式为指定时间

.. image:: ../_static/img/using/job/37.png


::

   点击授权按钮，可对数据进行权限设置，设置后该条数据获得相应的权限。

.. image:: ../_static/img/using/job/49.png


::

   点击表格列的显示与隐藏按钮。

.. image:: ../_static/img/using/job/50.png
.. image:: ../_static/img/using/job/51.png
.. image:: ../_static/img/using/job/52.png


::

   点击上方的搜索框可以根据模板以及时间进行数据查询和返回查询结果

.. image:: ../_static/img/using/job/39.png

.. image:: ../_static/img/using/job/38.png


::

   点击操作框内的修改按钮，可以修改当行数据

.. image:: ../_static/img/using/job/40.png

.. image:: ../_static/img/using/job/41.png


::

   点击操作框内的权限管理按钮，可以增加相应的权限

.. image:: ../_static/img/using/job/42.png


::

  点击权限管理按钮后进入用户权限设置以及团队权限设置两个页卡、在两个页面均可以新增、修改、查询、删除等操作。

.. image:: ../_static/img/using/job/43.png

.. image:: ../_static/img/using/job/44.png


::

  点击查看按钮后页面跳转到页面管理页面，并展示出该计划任务所执行的作业。

.. image:: ../_static/img/using/job/45.png

.. image:: ../_static/img/using/job/46.png


::

  点击删除按钮后删除此条数据。

.. image:: ../_static/img/using/job/47.png

.. image:: ../_static/img/using/job/48.png










