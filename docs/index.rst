==================
Pi超算集群用户文档
==================

`docs <https://docs.hpc.sjtu.edu.cn/>`_ 是上海交通大学 Pi2.0 超级计算集群用户文档，为用户提供快速上手指导和问题解答。如果想获取更多HPC团队的动态和信息，请访问 `上海交通大学HPC站点 <https://hpc.sjtu.edu.cn/>`_ 。   

.. caution:: *超算平台禁止**运行军工项目等涉密计算任务。*

.. tip:: 该文档通过 `github <https://github.com/SJTU-HPC/docs.hpc.sjtu.edu.cn>`_ 维护。如果您有什么建议或者意见，欢迎提交修改。 

.. 快速链接
.. ========
.. 
.. 1. :ref:`账号申请 <accountsapply>`
.. 2. :ref:`密码 <accountspasswords>`
.. 3. :ref:`远程登陆 <loginssh>`
.. 4. :ref:`远程桌面 <studiobasic>`
.. 5. :ref:`作业提交 <jobslurm>`
.. 6. :ref:`应用软件 <applications>`
.. 7. :ref:`使用GNU套件编译代码 <applicationsgnu>`
.. 8. :ref:`使用Intel套件编译代码 <applicationsintel>`
.. 9. :ref:`常见问题 <faq>`

.. toctree::
   :maxdepth: 1
   :caption: 账户

   accounts/apply
   accounts/passwords

.. toctree::
   :maxdepth: 1
   :caption: 登录

   login/ssh
   login/login
   login/tmux

.. toctree::
   :maxdepth: 1
   :caption: 可视化平台

   studio/basic
   studio/rdp
   studio/tmux

.. toctree::
   :maxdepth: 1
   :caption: 提交作业

   job/slurm
   job/jobssample1
   job/jobssample2
   job/dgx
   job/reservation

.. toctree::
   :maxdepth: 1
   :caption: 容器

   container/singularity
   container/u2cb

.. .. toctree::
..    :maxdepth: 1
..    :caption: 应用软件
.. 
..    app/index
..    app/module
..    app/conda
..    app/gnu
..    app/intel

.. toctree::
   :maxdepth: 1
   :caption: 常见问题

   faq/index