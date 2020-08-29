topic:
     Leverage Android Automated Testing to Assist Crowdsourced Testing
abstract:
     Crowdsourced testing is an emerged trend in the mobile application testing paradigm. Due to conducting large-scale user-oriented real scenarios, crowdsourced testing becomes an effective way to alleviate Android fragmentation problems. However, there is a lack of targeted guidance for crowdworkers, which leads crowdworkers to spend a lot of time to get familiar with the application under test. Consequently, it is difficult for crowdworkers to discover bugs in the application under test effectively and efficiently. 

In this paper, we leverage Android automated testing (i.e., dynamic analysis and static analysis) to guide crowdworkers to discover bugs in the app under test during crowdsourced testing. 
Our approach first performs dynamic analysis in the app under test. Besides, static analysis is adopted to supplement the results of dynamic analysis. Based on the fused results from dynamic analysis and static analysis, our approach automatically generates test tasks for crowdworkers. 
To assist crowdworkers in accomplishing test tasks, our approach further constructs a recommendation model to assign test tasks to crowdworkers and a guidance model to provide crowdworkers with the real-time path transition. 
We conduct evaluations on real-world Android applications, and the experimental results demonstrate our approach can improve the effectiveness and efficiency of crowdsourced testing. Moreover, the results from a user study show that our approach is useful for crowdworkers during crowdsourced testing.
process:
    1. First install APP Cloud Read, make sure the installed APP has a boot plug-in
    2. Start running the server program BugHunter, and start execution through the command spring-boot:run
    3. The test data in Bughunter comes from the data in SQL
    4. CloudReader-master is the source code with plugin
    5.CloudReader-master source code address https://github.com/youlookwhat/CloudReader.git
other:
    The data of other tested apk is still being processed
   