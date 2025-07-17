<style>

.reveal {
	font-size: 1.6em;
}

</style>


# AI and Cyber Security

by Loshana Aloka - Technical Support Engineer <br>
with NSBM ISACA Student Chapter

![me_online|128](attachments/me_online.jpeg)

notes:

Start to yap uncontrollably

---

![the_beginning_of_the_boom|600](attachments/the_beginning_of_the_boom.jpeg)

notes:

- So, AI is the big talk of the industry right now
- Remember Web 3 being the hype before that, 2019
- IoT, decentralized web and cloud services was the hype even before that
- Looking at AI, its surprising to see how far the industry has *innovated* in 2 two years
- DISCLAIMER : I do not know much about the technical aspects AI and ML

---

# What is "AI"?

TL;DR : Funny math functions that can do smart stuff (joking)

---

Algorithms trained on data that can be adapted to different scenarios to automate things.

Vendors provide generic AI models, variety of use cases but no specialty. These can be trained on specific data that are tailored to special use cases so they can perform better.

---

AI can usually be smart search engines because they can be used to parse ==unorganized data== quickly and extract useful information out from that data.

Just hope its *not* hallucinating.

---

The quality depends on how large the AI model is (number of parameters and supported context) and in the past couple of years, the consumer-grade models have gotten larger and larger.

![already_peaked|500](attachments/already_peaked.jpeg)

\- [Has Generative AI already peaked?](https://youtu.be/dDUC-LqVrPU) - Mike Pound \w Computerphile

---

The quality of training data also matters. Most data on the internet can be used with an AI model to answer common problems. But, as the topic gets more complex, it gets harder to train these models and receive a correct output.

![connors_phd_pt3|500](attachments/connors_phd_pt3.png)

\- [Hacking the Learning Curve](https://youtu.be/qjOBDE_atIk) - Dr. Connor Nelson's PhD Defense @ pwn.college

---

# Use cases in Cyber

## Attack & Defense

---

### How do good guys use them?

Most defense teams utilize these by ingesting it with streams of events. They can use these models, even generic, to enrich the data tied to events and then feed them to EDR platforms.

---

![crowdstrike_ti](attachments/crowdstrike_ti.png)

![wazuh_ingestion](attachments/wazuh_ingestion.png)

---

![unsupervised_approach_local_research|500](attachments/unsupervised_approach_local_research.jpeg)

\- http://ir.lib.ruh.ac.lk/handle/iruor/19733

notes:

Smart Shield was also presented in BSides Sri Lanka this year

---

End