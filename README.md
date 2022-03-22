# Linux
<기본 명령어와 파일 시스템>
2018974031 이현수
1. cegw.ks.ac.kr (IP주소 202.30.32.20) 리눅스 컴퓨터에 접속하여 다음 명령을 내린 후 각각의 결과 화면을 보여라.
dlgustn4020@cegw:~$ who
ysw2603  pts/0        2022-03-22 19:20 (221.161.59.60)
dlgustn4020 pts/1        2022-03-22 19:30 (118.47.139.232)

dlgustn4020@cegw:~$ date
2022. 03. 22. (화) 19:32:30 KST

dlgustn4020@cegw:~$ cal
      3월 2022
일 월 화 수 목 금 토
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31

dlgustn4020@cegw:~$ cal 2022
                            2022
         1월                    2월                    3월
일 월 화 수 목 금 토  일 월 화 수 목 금 토  일 월 화 수 목 금 토
                   1         1  2  3  4  5         1  2  3  4  5
 2  3  4  5  6  7  8   6  7  8  9 10 11 12   6  7  8  9 10 11 12
 9 10 11 12 13 14 15  13 14 15 16 17 18 19  13 14 15 16 17 18 19
16 17 18 19 20 21 22  20 21 22 23 24 25 26  20 21 22 23 24 25 26
23 24 25 26 27 28 29  27 28                 27 28 29 30 31
30 31

         4월                    5월                    6월
일 월 화 수 목 금 토  일 월 화 수 목 금 토  일 월 화 수 목 금 토
                1  2   1  2  3  4  5  6  7            1  2  3  4
 3  4  5  6  7  8  9   8  9 10 11 12 13 14   5  6  7  8  9 10 11
10 11 12 13 14 15 16  15 16 17 18 19 20 21  12 13 14 15 16 17 18
17 18 19 20 21 22 23  22 23 24 25 26 27 28  19 20 21 22 23 24 25
24 25 26 27 28 29 30  29 30 31              26 27 28 29 30


         7월                    8월                    9월
일 월 화 수 목 금 토  일 월 화 수 목 금 토  일 월 화 수 목 금 토
                1  2      1  2  3  4  5  6               1  2  3
 3  4  5  6  7  8  9   7  8  9 10 11 12 13   4  5  6  7  8  9 10
10 11 12 13 14 15 16  14 15 16 17 18 19 20  11 12 13 14 15 16 17
17 18 19 20 21 22 23  21 22 23 24 25 26 27  18 19 20 21 22 23 24
24 25 26 27 28 29 30  28 29 30 31           25 26 27 28 29 30
31

        10월                   11월                   12월
일 월 화 수 목 금 토  일 월 화 수 목 금 토  일 월 화 수 목 금 토
                   1         1  2  3  4  5               1  2  3
 2  3  4  5  6  7  8   6  7  8  9 10 11 12   4  5  6  7  8  9 10
 9 10 11 12 13 14 15  13 14 15 16 17 18 19  11 12 13 14 15 16 17
16 17 18 19 20 21 22  20 21 22 23 24 25 26  18 19 20 21 22 23 24
23 24 25 26 27 28 29  27 28 29 30           25 26 27 28 29 30 31
30 31

dlgustn4020@cegw:~$ uptime
 19:33:56 up 26 days,  5:19,  2 users,  load average: 0.24, 0.21, 0.18

dlgustn4020@cegw:~$ whoami
dlgustn4020

2. 이 리눅스 컴퓨터의 하드 디스크 총용량은 얼마이며 (단위: GB), 가용 공간은 얼마인가?
답:
하드 디스크 총용량: 266.923 GB
가용 공간: 241.149 GB
dlgustn4020@cegw:~$ df -h
Filesystem      Size  Used Avail Use% Mounted on
udev            7.8G     0  7.8G   0% /dev
tmpfs           1.6G  1.7M  1.6G   1% /run
/dev/sdc1        28G   12G   15G  44% /
tmpfs           7.9G     0  7.9G   0% /dev/shm
tmpfs           5.0M  4.0K  5.0M   1% /run/lock
tmpfs           7.9G     0  7.9G   0% /sys/fs/cgroup
/dev/loop0      640K  640K     0 100% /snap/gnome-logs/106
/dev/loop2      248M  248M     0 100% /snap/gnome-3-38-2004/87
/dev/loop4      2.3M  2.3M     0 100% /snap/gnome-system-monitor/157
/dev/loop5      219M  219M     0 100% /snap/gnome-3-34-1804/72
/dev/loop3       66M   66M     0 100% /snap/gtk-common-themes/1515
/dev/loop6      2.7M  2.7M     0 100% /snap/gnome-calculator/920
/dev/loop9       66M   66M     0 100% /snap/gtk-common-themes/1519
/dev/loop8      768K  768K     0 100% /snap/gnome-characters/761
/dev/loop7       56M   56M     0 100% /snap/core18/2284
/dev/loop10     128K  128K     0 100% /snap/bare/5
/dev/loop11     141M  141M     0 100% /snap/gnome-3-26-1604/102
/dev/loop14     2.7M  2.7M     0 100% /snap/gnome-system-monitor/174
/dev/loop16     640K  640K     0 100% /snap/gnome-logs/103
/dev/loop17     163M  163M     0 100% /snap/gnome-3-28-1804/145
/dev/loop18     165M  165M     0 100% /snap/gnome-3-28-1804/161
/dev/loop19     768K  768K     0 100% /snap/gnome-characters/741
/dev/loop20     2.5M  2.5M     0 100% /snap/gnome-calculator/884
/dev/loop22     219M  219M     0 100% /snap/gnome-3-34-1804/77
/dev/loop21     249M  249M     0 100% /snap/gnome-3-38-2004/99
/dev/loop24     141M  141M     0 100% /snap/gnome-3-26-1604/104
/dev/sdc2       207G  416M  196G   1% /home
tmpfs           1.6G   16K  1.6G   1% /run/user/121
/dev/loop25      62M   62M     0 100% /snap/core20/1361
/dev/loop12     111M  111M     0 100% /snap/core/12725
/dev/loop13      62M   62M     0 100% /snap/core20/1376
/dev/loop15     111M  111M     0 100% /snap/core/12821
/dev/loop23      56M   56M     0 100% /snap/core18/2344
tmpfs           1.6G     0  1.6G   0% /run/user/1003
tmpfs           1.6G     0  1.6G   0% /run/user/1013
tmpfs           1.6G     0  1.6G   0% /run/user/1033


3. 이 리눅스 컴퓨터의 메인 메모리 총용량은 얼마이며 (단위: GB), 가용 공간은 얼마인가?
답: 
메인 메모리 총용량: 15 GB
가용 공간: 14.436 GB
dlgustn4020@cegw:~$ free -h
              total        used        free      shared  buff/cache   available
Mem:            15G        563M         11G        1.8M        3.9G         14G
스왑:        1.3G          0B        1.3G

4. 다음 명령은 각각 어떤 일을 하는가?
passwd: 계정의 비밀번호를 변경하는 명령어입니다.
dlgustn4020@cegw:~$ passwd
dlgustn4020에 대한 암호 변경 중

finger: 사용자들의 계정 정보를 확인하는 명령어입니다.
dlgustn4020@cegw:~$ finger
Login        Name           Tty      Idle  Login Time   Office     Office Phone
dlgustn4020  leehyunsu      pts/1          Mar 22 20:52 (118.47.139.232)
honeyhyun2   HeoHyun        pts/2          Mar 22 19:44 (61.78.235.105)
ysw2603      YOONSEONGWON   pts/0          Mar 22 19:20 (221.161.59.60)


last: 사용자들 중 제일 최근에 접속한 계정부터 나열되는 리스트를 확인 할 수 있는 명령어입니다.
dlgustn4020@cegw:~$ last
dlgustn4 pts/1        118.47.139.232   Tue Mar 22 20:52   still logged in
honeyhyu pts/2        61.78.235.105    Tue Mar 22 19:44   still logged in
dlgustn4 pts/1        118.47.139.232   Tue Mar 22 19:30 - 20:52  (01:21)
ysw2603  pts/0        221.161.59.60    Tue Mar 22 19:20   still logged in
wjdehdnr pts/1        121.145.165.163  Tue Mar 22 16:43 - 16:43  (00:00)
.
.
.

w: 접속해 있는 사용자들의 정보와 서버 정보를 보여주는 명령어입니다.
dlgustn4020@cegw:~$ w
 20:57:56 up 26 days,  6:43,  3 users,  load average: 0.20, 0.22, 0.19
USER     TTY      FROM             LOGIN@   IDLE   JCPU   PCPU WHAT
ysw2603  pts/0    221.161.59.60    19:20    2:36   0.06s  0.06s -bash
dlgustn4 pts/1    118.47.139.232   20:52    0.00s  0.05s  0.00s w
honeyhyu pts/2    61.78.235.105    19:44    3:48   0.08s  0.08s -bash

pwd: 현재 작업중인 디렉토리 위치를 출력하는 명령어입니다.
dlgustn4020@cegw:~$ pwd
/home/dlgustn4020

5. 다음 명령의 의미는 각각 무엇인가?
$ cd ~hjyang: 작업 디렉토리를 hjyang 홈디렉토리로 변경합니다.
		    즉, hjyang 디렉토리로 이동합니다.

$ cd ..: 한 단계 상위 디렉토리로 이동합니다.

$ cd /etc/init.d: etc 디렉토리 안에 있는 init.d 디렉토리로 이동합니다.
      즉, 절대 경로를 사용하여 이동합니다. 

$ cd ../../bin: 상위 디렉토리로 2번 이동한 후 bin 디렉토리로 이동합니다.

$ cd: 작업 디렉토리를 홈디렉토리로 변경합니다.

6. ls 명령의 -a, -l, -F, -r, -s, -S, -t 옵션의 사용 용도에 대해 각각 설명하라.
-a: 

-l:

-F:

-r:

-s:

-S:

-t:

7. 리눅스 파일 시스템 계층 구조에서 다음 디렉토리들이 각각 무슨 용도로 사용되는지 설명하라.

/bin /dev /etc /lib /tmp /usr /var /home

8. 2000년 1월의 달력을 화면에 출력하는 명령은 무엇인가?

9. 작업 디렉토리 working directory 란 무엇을 의미하는가?

10. 홈 디렉토리 home directory 란 무엇을 의미하는가?

11. 작업 디렉토리를 hjyang 계정 사용자의 홈 디렉토리로 이동하려면 어떻게 해야 하는가?

12. 현재 디렉토리에 있는 모든 파일들의 이름을 날짜의 역순으로 보이게 하려면 어떻게 해야 하는가?

13. 자신의 사용자 암호 user password 를 바꾸려면 어떻게 해야 하는가?
