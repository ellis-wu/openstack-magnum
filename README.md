# Magnum

Magnum 由 OpenStack Container Team 開發的```container orchestration engines```，像是 Docker 和 Kubernetes 可作為 OpenStack 上第一類資源開發的 OpenStack API 服務。Magnum 使用 Heat 來編配(orchestrate) OS 映像檔(image)，其中包含 Docker 和 Kubernetes，並依照叢集配置執行在任何的虛擬機或裸機(bare metal)中。

## 最新消息
* 2015-10-20 We have published a list of [sessions to attend](https://wiki.openstack.org/wiki/Magnum/Summit) at the Mitaka Design Summit in Tokyo
* 2015-08-26 Magnum will be presenting [a session on Magnum](http://sched.co/49xE) at the 2015 OpenStack Summit in Tokyo on October 28 4:40pm - 5:20pm [Video](https://www.openstack.org/summit/tokyo-2015/videos/presentation/openstack-magnum-containers-as-a-service)
* 2015-05-21 We presented [a session on Magnum](https://openstacksummitmay2015vancouver.sched.org/event/ec3936678ef22681408088ec52a4e80b) at the 2015 OpenStack Summit in Vancouver on Thursday, May 21 9:00am - 9:40am US/Pacific. [Video](https://www.openstack.org/summit/vancouver-2015/summit-videos/presentation/magnum-containers-as-a-service-for-openstack)
* 2015-03-24 Magnum has [officially joined](https://review.openstack.org/161080) the OpenStack project list upon approval by a unanimous vote by the Technical Committee.
* 2015-03-09 Our Kilo-2 release is now available for download.
* 2015-01-20 We have announced Magnum's first release, now available for download.

## 如何開始與下載
開始使用 Magnum 請參考：[快速開始手冊](http://docs.openstack.org/developer/magnum/dev/dev-quickstart.html)

版本 1.0.0.0b1 (Liberty Beta 1)下載：
* [magnum](http://tarballs.openstack.org/magnum/magnum-1.0.0.0b1.tar.gz)
* [python-magnumclient](http://tarballs.openstack.org/python-magnumclient/python-magnumclient-1.0.0.0b1.tar.gz)

## 貢獻
該專案由我們 OpenStack Containers Team 積極開發。我們每週使用 [IRC](https://wiki.openstack.org/wiki/Meetings/Containers) 進行會議討論，而會議通常由 PTL [Adrian Otto](https://launchpad.net/~aotto) 主持。
	* 我們需要您[貢獻 Magnum](https://wiki.openstack.org/wiki/Magnum/Contributing)!

## 架構
![magnum_architecture](./Magnum_architecture.png)
Bay Create/Update/Delete

## 參考資料
* Launchpad Project Pages
	* [Magnum Launchpad Project](http://launchpad.net/magnum) for Blueprints
	* [python-magnumclient Launchpad Project](http://launchpad.net/python-magnumclient) for Blueprints
* Mailing List
	* [OpenStack Mailing List](http://lists.openstack.org/cgi-bin/mailman/listinfo/openstack-dev) for project related discussion
		* Add [Magnum] to the subject line of new posts about this project.
	* [OpenStack Mailing List Archives](http://lists.openstack.org/pipermail/openstack-dev/) for current discussion.
* Code Reviews
	* [Gerrit Reviews](https://review.openstack.org/#/q/status:open+magnum,n,z)
* Code Repository
	* git clone [git://git.openstack.org/openstack/magnum](git://git.openstack.org/openstack/magnum)
* Specification
	* [Containers Service Spec](https://review.openstack.org/136103)
	* [Container Networking Model Spec](https://review.openstack.org/204686/)
* References
	* [Magnum Networking Details](https://wiki.openstack.org/wiki/Magnum/Networking)
	* [Network Driver Support Matrix](https://wiki.openstack.org/wiki/Magnum/NetworkDriverMatrix)
	* [Labels Support Matrix](https://wiki.openstack.org/wiki/Magnum/LabelMatrix)
	* [Acronyms](https://wiki.openstack.org/wiki/Magnum/Acronyms)
	* [IRC Logs - OpenStack Containers](http://eavesdrop.openstack.org/irclogs/%23openstack-containers/)
	* [Meeting Minutes - OpenStack Containers](http://eavesdrop.openstack.org/meetings/containers/2015/)

## IRC


