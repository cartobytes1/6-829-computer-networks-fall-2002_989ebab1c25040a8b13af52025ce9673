---
course_id: 6-829-computer-networks-fall-2002
layout: course_section
menu:
  leftnav:
    identifier: 065ed03cb61ce97b68cc671caa24bb9a
    name: Readings
    weight: 30
title: Readings
type: course
uid: 065ed03cb61ce97b68cc671caa24bb9a

---

The readings listed on this page are in three parts. First come the background readings. You will find them useful to get up to speed. Then come the assigned readings. Finally, we list several papers as optional readings, for you to learn more about specific topics. The schedule provides hints on when any given optional reading might be useful. All papers are named by shorthand names such as CK74.

Background (will not be explicitly discussed in class)
------------------------------------------------------

**\[SRC84\]** Saltzer, J., D. Reed, and D. Clark. "End-to-end Arguments in System Design." [_ACM Transactions on Computer Systems (TOCS)_](http://www.acm.org/tocs/) 2, no. 4 (1984): 195-206. (This paper is covered in 6.033.)

Ethernet paper.

**\[L0\]** Balakrishnan, H. "Single-link Communication." 6.829 Computer Networks Lecture Notes, Fall 2002. (Read this before or soon after first lecture.) ([PDF]({{< baseurl >}}/sections/lecture-notes/l0singlelink))

Assigned Readings (by Topic Area)
---------------------------------

### Part I. Internetworking and Routing

**Internet Architecture**

**\[CK74\]** Cerf, V., and [R. Kahn](http://www.cnri.reston.va.us/bios/kahn.html). "A Protocol for Packet Network Interconnection." [_IEEE Transactions on Communications_](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=26) COM-22 (1974): 637-648.

**\[Cla88\]** Clark, D. "Design Philosophy of the DARPA Internet Protocol." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm)_ (August 1988): 106-114. Stanford, CA.

**\[Hin96\]** Hinden, R. "IP Next Generation Overview." _Comm of the ACM_ 39, no. 6 (June 1996): 61-71.

**Unicast IP Forwarding and Routing**

**\[BCDP97\]** Brodnik, A., S. Carlsson, M. Degermark, and S. Pink. "[Small Forwarding Tables for Fast Routing Lookups](http://www.acm.org/sigcomm/sigcomm97/papers/p192.html)." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (September [1997](http://www.acm.org/sigcomm/sigcomm97/)). Cannes, France.

**\[L4\]** Balakrishnan, H. "Wide-area Unicast Routing." 6.829 Computer Networks Lecture Notes, Fall 2002. ([PDF]({{< baseurl >}}/sections/lecture-notes/l4unicastrtg))

**Internet Routing in-the-Wild (Measurement)**

**\[Pax97\]** Paxson, V. "End-to-End Routing Behavior in the Internet." [_IEEE/ACM Transactions on Networking_](https://ton.lids.mit.edu/) 5, no. 5 (October 1997): 601-615.

**Big Fast Routers**

**\[P+98\]** Partridge, C., et al. "A 50 Gb/s IP Router." [_IEEE/ACM Transactions on Networking_](https://ton.lids.mit.edu/) 6, no. 3 (June 1998): 237-248.

**\[McK96\]** McKeown, N., M. Izzard, A. Mekkittikul, W. Ellersick, and M. Horowitz. "The Tiny Tera: A Packet Switch Core." _Proc Hot Interconnects_ V (August 1996). Stanford University.

**Security Issues in the Internet Architecture**

**\[Bel89\]** Bellovin, Steven M. "Security Problems in the TCP/IP Protocol Suite ([PDF](http://www.cs.columbia.edu/~smb/papers/ipext.pdf))." _Computer Communications Review_ 2, no. 19 (April 1989): 32-48.

**\[Sno+01\]** Snoeren, A., C. Partridge, L. Sanchez, C. Jones, F. Tchakountio, S. Kent, and T. Strayer. "[Hash-based IP Traceback](http://www.acm.org/sigcomm/sigcomm2001/p1.html)." _Proc ACM SIGCOMM_ (August [2001](http://www.acm.org/sigcomm/sigcomm2001/)). San Diego, CA.

**Robustness**

**\[ASSW02\]** Anderson, T., S. Shenker, I. Stoica, and D. Wetherall. "Towards More Robust Internet Protocols." (July 2002).

Part II. Resource Management
----------------------------

**End-to-End Congestion Control**

**\[JK88\]** Jacobson, V., and M. Karels. "Congestion Avoidance and Control." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm)_ (August 1988). Stanford, CA.

**\[CJ89\]** Chiu, and D. M., and R. Jain. "Analysis of the Increase and Decrease Algorithms for Congestion Avoidance in Computer Networks." _Computer Networks and ISDN Systems_ 17 (1989): 1-14.

**Router-Assisted Congestion Control, Active Queue Management, and Scheduling**

**\[FJ93\]** [Floyd, S.](http://www.aciri.org/floyd/), and V. Jacobson. "Random Early Detection Gateways for Congestion Avoidance." [_IEEE/ACM Transactions on Networking_](https://ton.lids.mit.edu/) 1, no. 4 (August 1993): 397-413.

**\[KHR02\]** Katabi, D., M. Handley, and C. Rohrs. "[Congestion control for high bandwidth-delay product networks](http://www.acm.org/sigcomm/sigcomm2002/papers/xcp.html)." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm/) (August 2002). Pittsburgh, PA.

**\[DKS90\]** Demers, A., S. Keshav, and [S. Shenker](http://www.aciri.org/shenker/). "Analysis and Simulation of a Fair Queueing Algorithm." _Internetworking: Research and Experience_ 1, no. 1 (1990): 3-26. (If you like, you may also read the slightly older SIGCOMM '89 version.)

**\[SSZ98\]** [Stoica, I.](http://www.cs.berkeley.edu/~istoica/), [S. Shenker](http://www.aciri.org/shenker/), and [H. Zhang](http://www.cs.cmu.edu/%7Ehzhang/). "Core - Stateless Fair Queueing: Achieving Approximately Fair Allocations in High Speed Networks." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm/) (September [1998](http://www.acm.org/sigcomm/sigcomm98/)). Vancouver, Canada. ASIN: B0006R9W38.

**Modeling and Measurement**

**\[JD02\]** Jain, M., and C. Dovrolis. "[End-to-end Available Bandwidth: Measurement Methodology, Dynamics, and Relation with TCP Throughput](http://www.acm.org/sigcomm/sigcomm2002/papers/e2ebw.html)." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (August 2002). Pittsburgh, PA.

**\[WGJPS02\]** Willinger, W., R. Govindan, S. Jamin, V. Paxson, and S. Shenker. "[Scaling phenomena in the Internet: Critically examining criticality](http://www.pnas.org/cgi/content/full/99/suppl_1/2573)." _Proc Natl Acad Sci USA_ 99, supplement 1 (February 19, 2002): 2573-2580.

**\[SPW02\]** Staniford, S., V. Paxson, and N. Weaver. "[How to 0wn the Internet in Your Spare Time](http://www.icir.org/vern/papers/cdc-usenix-sec02/)." _Proc USENIX Security Symp_ (August 2002). San Francisco, CA.

**Adaptive Applications and Internet QoS**

**\[CT90\]** Clark, D., and D. Tennenhouse. "Architectural Consideration for a New Generation of Protocols." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (September 1990). Philadelphia, PA.

**\[BSR99\]** Balakrishnan, H., [S. Seshan](http://www.seshan.org/), and H. Rahul. "An Integrated Congestion Management Architecture for Internet Hosts." _Proc ACM SIGCOMM_ (September [1999](http://www.acm.org/sigcomm/sigcomm99/)). Cambridge, MA.

**\[She95\]** Shenker, S. "Fundamental Design Issues for the Future Internet." _IEEE Journal on Selected Areas in Communications_ 13, no. 7 (September 1995): 1176-1188.

**\[CSZ92\]** Clark, D., [S. Shenker](http://www.aciri.org/shenker), and L. Zhang. "Supporting Real-Time Applications in an Integrated Services Packet Network: Architecture and Mechanisms." _Proc [SIGCOMM](http://www.acm.org/sigcomm) '92 (_ August 1992). Baltimore, MD.

**\[CF98\]** Clark, D., and W. Feng. "Explicit Allocation of Best-Effort Packet Delivery Service." [_IEEE/ACM Transactions on Networking_](https://ton.lids.mit.edu/) 6, no.4 (August 1998): 362-373.

Part III. Network Services
--------------------------

**Wireless/Mobile Networking**

**\[BMJ+98\]** Broch, J., D. Maltz, [D. Johnson](http://www.cs.cmu.edu/%7Edbj/), Y. C. Hu, and J. Jetcheva. "A Performance Comparison of Multi-Hop Wireless Ad Hoc Routing Protocols." _Proc ACM MOBICOM_ (August 1998). Dallas, TX.

**\[IGE00\]** Intanagonwiwat, C., [R. Govindan](https://viterbi.usc.edu/directory/faculty/Govindan/Ramesh), and [D. Estrin](http://tech.cornell.edu/people/deborah-estrin). "[Directed diffusion: A scalable and robust communication paradigm for sensor networks](http://dx.doi.org/10.1145/345910.345920)." _Proc ACM MOBICOM_ (August 2000). Boston, MA.

**\[BDSZ94\]** Bharghavan, V., A. Demers, [S. Shenker](http://www.aciri.org/shenker/), and L. Zhang. "MACAW: A Media Access Protocol for Wireless LANs." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (September 1994): 212-225. London, UK.

**\[BSK95\]** Balakrishnan, H., [S. Seshan](http://www-2.cs.cmu.edu/~srini/), and [R. Katz](http://www.cs.berkeley.edu/%7Erandy/). "Improving Reliable Transport and Handoff Performance in Cellular Wireless Networks." _ACM Wireless Networks_ 1, no. 4 (December 1995).

**Naming: DNS**

**\[JSBM01\]** Jung, J., E. Sit, H. Balakrishnan, and R. Morris. "DNS Performance and the Effectiveness of Caching." _Proc ACM SIGCOMM Internet Measurement Workshop_ (November 2001). San Francisco, CA. ([PDF](http://conferences.sigcomm.org/imc/2001/imw2001-papers/89.pdf))

**Peer-to-Peer Networking, Distributed Hash Tables**

**\[SMKKB01\]** [Stoica, I.](http://www.cs.berkeley.edu/%7Eistoica/), R. Morris, D. Karger, M. Kaashoek, and H. Balakrishnan. "Chord: A Scalable Peer-to-peer Lookup Service for Internet Applications." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm/) (August [2001](http://www.acm.org/sigcomm/sigcomm2001/)). San Diego, CA.

**\[BKKMS03\]** ———. Looking Up Data in P2P Systems, _Comm. of the ACM_ (February 2003).

**\[CSWH00\]** Clarke, I., O. Sandberg, B. Wiley, and T. Hong. "Freenet: A Distributed Anonymous Information Storage and Retrieval System." _Proc ICSI Workshop on Design Issues in Anonymity and Unobservability_ (July 2000). Berkeley, CA.

**Overlay Routing**

**\[ABKM01\]** [Andersen, D.](http://www.angio.net/personal/), H. Balakrishnan, M. Kaashoek, and R. Morris. "Resilient Overlay Networks." _Proc 18th ACM SOSP_ (October 2001). Banff, Canada.

**\[Sto+02\]** [Stoica, I.](http://www.cs.berkeley.edu/%7Eistoica/), D. Adkins, S. Zhuang, S. Shenker, and S. Surana. "[Internet Indirection Infrastructure](http://www.acm.org/sigcomm/sigcomm2002/papers/i3.html)." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (August 2002). Pittsburgh, PA.

**Multicast**

**\[MS97\]** Maufer, T., and C. Semeria. "Introduction to IP Multicast Routing." Internet-Draft, July 1997.

**\[F+97\]** [Floyd, S.](http://www.icir.org/floyd/), V. Jacobson, C. Liu, S. McCanne, and L. Zhang. "A Reliable Multicast Framework for Light-Weight Sessions and Application Level Framing." [_IEEE/ACM Transactions on Networking_](http://www.ton.cc.gatech.edu/) (1997).

**Optional Additional Readings and References**

**\[LABJ00\]** Labovitz, C., A. Ahuja, A. Bose, and F. Jahanian. "Delayed Internet Routing Convergence." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm/sigcomm2000/conf/paper/sigcomm2000-5-2.pdf) (September [2000](http://www.acm.org/sigcomm/sigcomm2000/)): 175-187. Stockholm, Sweden.

**\[Nor00\]** Norton, W. "Internet Service Providers and Peering." 2000.

**\[BV01\]** Baboescu, F., and G. Varghese. "Scalable Packet Classification." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (August [2001](http://www.acm.org/sigcomm/sigcomm2001/)). San Diego, CA.

**Network Protection**

**\[SWKA00\]** [Savage, S.](https://cseweb.ucsd.edu/~savage/), [D. Wetherall](https://www.coursera.org/instructor/~517478), [A. Karlin](http://www.cs.washington.edu/homes/karlin), and [T. Anderson](https://www.cs.washington.edu/people/faculty/tom). "Practical Network Support for IP Traceback." _Proc ACM SIGCOMM_ September [2000](http://www.acm.org/sigcomm/sigcomm2000/conf/paper/sigcomm2000-8-4.pdf). Stockholm, Sweden. ([PDF](http://www.acm.org/sigcomm/sigcomm2000/conf/paper/sigcomm2000-8-4.pdf))

**Reliable Transport and Congestion Control**

**\[FF96\]** Floyd, S., and K. Fall. "A Simulation Comparison of Tahoe, Reno, and SACK TCP." _ACM SIGCOMM CCR_ (1996).

**\[FF99\]** [Floyd, S.](http://www.aciri.org/floyd), and K. Fall. "[Promoting the Use of End-to-End Congestion Control in the Internet](http://www.aciri.org/floyd/end2end-paper.html)." [_IEEE/ACM Transactions on Networking_](http://www.ton.cc.gatech.edu/) 7, no. 4 (August 1999): 458-472.

**\[RJ90\]** Ramakrishnan, K. K., and R. Jain. "A Binary Feedback Scheme for Congestion Avoidance in Computer Networks." [_ACM Transactions on Computer Systems (TOCS)_](http://www.acm.org/tocs/) 8, no. 2 (May 1990): 158-181.

**\[FHPW01\]** Floyd, S., M. Handley, J. Padhye, and J. Widmer. "Equation-Based Congestion Control for Unicast Applications." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (August [2000](http://www.acm.org/sigcomm/sigcomm2000/)). Stockholm, Sweden. ([PDF](http://www.icir.org/tfrc/tcp-friendly.pdf))

**\[BB01\]** Bansal, D., and H. Balakrishnan. "Binomial Congestion Control Algorithm." _Proc IEEE INFOCOM_ (April 2001). Anchorage, AK.

**\[SEW01\]** Spring, N., D. Ely, D. Wetherall, S. Savage, and T. Anderson. "Robust ECN Signaling." _Proc International Conf on Network Protocols_ (November 2001). Riverside, CA.

**Unicast Routing**

**\[Huitema96\]** Huitema, C. _Routing in the Internet_. Upper Saddle River, NJ: Prentice Hall, January 15, 2000. ISBN: 0130226475. ([Search](http://vig.prenhall.com/search) for Huitema on the Prentice Hall site.)

**\[LMJ97\]** Labovitz, C., R. Malan, and F. Jahanian. "[Internet Routing Instability](http://www.acm.org/sigcomm/sigcomm97/papers/p109.html)." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (September [1997](http://www.acm.org/sigcomm/sigcomm97/)). Cannes, France.

**\[Stewart99\]** Stewart, J. _BGP4 Inter-Domain Routing in the Internet_. Reading, MA: Addison-Wesley, January 1999. ISBN: 0201379511.

**\[Tsu88\]** Tsuchiya, P. "The Landmark Hierarchy: A New Hierarchy for Routing in Very Large Networks." _Proc ACM SIGCOMM_ (August 1988): 35-42. Stanford, CA.

**Adaptive and Network-Aware Applications**

**\[PM95\]** [Padmanabhan, V.](http://www.cs.berkeley.edu/%7Epadmanab/), and J. Mogul. "Improving HTTP Latency." _Computer Networks and ISDN Systems_ 28 (December 1995): 25-35.

**\[RHE99\]** Rejaie, R., [M. Handley](http://www.cs.ucl.ac.uk/staff/m.handley/), and [D. Estrin](http://tech.cornell.edu/people/deborah-estrin). "[Quality Adaptation for Congestion Controlled Video Playback over the Internet](http://www.acm.org/sigs/sigcomm/sigcomm99/papers/session5-3.html)." [_Proc ACM SIGCOMM_](http://www.acm.org/sigcomm/sigcomm99/) (September 1999).

**Traffic Engineering, Flow Modeling**

**\[Elw01\]** Elwalid, A., C. Jin, S. Low, and I. Widjaja. "MATE: MPLS Adaptive Traffic Engineering." _Proc IEEE INFOCOM_ (2001). Anchorage, AK.

**\[EV02\]** Estan, C., and G. Varghese. "[New directions in traffic measurement and accounting](http://www.acm.org/sigcomm/sigcomm2002/papers/account.html)." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm/)_ (August 2002). Pittsburgh, PA.

**Multicast Routing/Transport**

**\[DC90\]** Deering, S., and [D. Cheriton](http://www.stanford.edu/~cheriton/). "Multicast Routing in Datagram Internetworks and Extended LANs." [_ACM Transactions on Computer Systems (TOCS)_](http://www.acm.org/tocs/) 8, no. 2 (May 1990): 85-110.

**\[DE+94\]** Deering, S., [D. Estrin](http://tech.cornell.edu/people/deborah-estrin), D. Farinacci, V. Jacobson, C. G. Liu, and L. Wei. "An Architecture for Wide-Area Multicast Routing." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (September 1994). London, UK.

**\[HC99\]** Holbrook, H., and D. Cheriton. "IP Multicast Channels: EXPRESS Support for Large-scale Single-source Applications." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/) (September [1999](http://www.acm.org/sigcomm/sigcomm99/)). Cambridge, MA.

**\[MJV96\]** McCanne, S., V. Jacobson, and [M. Vetterli](https://lcav.epfl.ch/martin-vetterli/). "Receiver-driven Layered Multicast." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (August 1996). Stanford, CA.

**\[Pap98\]** Papadopoulos, C. "[An Error Control Scheme for Large-Scale Multicast Applications](http://www.ccrc.wustl.edu/)." _Proc IEEE INFOCOM '98_ (March 1998). San Francisco, CA.

**\[BTW94\]** Turletti, T., and I. Wakeman. "Scalable Feedback Control for Multicast Video Distribution in the Internet." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (September 1994). [London](http://www.ucl.ac.uk/), UK.

**Wireless Protocols**

**\[Joh96\]** [Johnson, D.](http://www.cs.cmu.edu/%7Edbj/) "Scalable Support for Transparent Mobile Host Internetworking." Chapter 3 in _Mobile Computing._ Edited by T. Imielinski and H. Korth. Kluwer Academic Publishers, 1996, pp. 103-128.

**\[SB00\]** Snoeren, A., and H. Balakrishnan. "An End-to-End Approach to Host Mobility." _Proc_ [_ACM MOBICOM_](http://www.acm.org/sigmobile) (August 2000). Boston, MA.

**\[She96\]** Shepard, T. J. "A Channel Access Scheme for Large Dense Packet Radio Networks." _Proc ACM SIGCOMM_ (August 1996). Stanford, CA.

**\[J+01\]** Li, J., C. Blake, D. De Couto, H. Lee, and R. Morris. "Capacity of Wireless Ad Hoc Networks." _Proc_ [_ACM MOBICOM_](http://www.acm.org/sigmobile/) (July 2001). Rome, Italy.

**\[CJBM01\]** Chen, B., K. Jamieson, H. Balakrishnan, and R. Morris. "Span: An Energy-Efficient Coordination Algorithm for Topology Maintenance in Ad Hoc Wireless Networks." _Proc_ [_ACM MOBICOM_](http://www.acm.org/sigmobile/) (July 2001). Rome, Italy.

Naming
------

**\[MD88\]** Mockapetris, P., and K. Dunlap. "Development of the Domain Name System." _Proc [ACM SIGCOMM](http://www.acm.org/sigcomm)_ (August 1988). [Stanford](http://www.stanford.edu/), CA.

Web Caching
-----------

**\[FCAB98\]** Fan, L., P. Cao, J. Almeida, and A. Broder. "[Summary Cache: A Scalable Wide-Area Cache Sharing Protocol](http://www.acm.org/sigcomm/sigcomm98/tp/abs_21.html)." [_Proc SIGCOMM '98_](http://www.acm.org/sigcomm/sigcomm98) (September 1998): 254-265. Vancouver, Canada.

Introducing New Services: Overlays v. Active Networks
-----------------------------------------------------

**\[W99\]** [Wetherall, D.](https://www.coursera.org/instructor/~517478) "Active network vision and reality: Lessons from a capsule-based system." _Proc_ [_17th SOSP_](http://www.acm.org/sigs/sigops/sosp99/) December 1999. Kiawah Island, SC. (![This resource may not render correctly in a screen reader.](/images/inacessible.gif)[PDF](http://research.microsoft.com/en-us/um/people/padmanab/cse561/papers/wet99.pdf))

**Modeling and Measurement**

**\[Pax97\]** Paxson, V. "[End-to-End Internet Packet Dynamics](http://www.acm.org/sigcomm/sigcomm97/papers/p086.html)." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm/) (September 1997): 139-152. Cannes, France.

**\[Bol93\]** Bolot, J. C. "End-to-End Packet Delay and Loss Behavior in the Internet." _Proc_ [_ACM SIGCOMM_](http://www.acm.org/sigcomm) (August 1993). San Francisco, CA.

**\[LTWW94\]** Leland, W. E., M. S. Taqqu, W. Willinger, and D. V. Wilson. "On the Self-Similar Nature of Ethernet Traffic." [_IEEE/ACM Transactions on Networking_](http://www.ton.cc.gatech.edu/) 2, no. 1 (February 1994): 1-15.

Paper on Topology Modeling.