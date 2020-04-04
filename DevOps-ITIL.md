# continuous delivery and change management

both devops and ITIL have best practices for bringing software changes in production.

## goals

- stable products
- products that are fit for purpose
- short lead time (metric from the devops world), adequate time-to-market for new products (universally applicable)

## what devops says

- small, frequent changes
- fully automated ci/cd pipeline
- canary or blue/green deployment
- infrastructure-as-code

## what itil says

- different change types (normal, standard and emergency changes)
- risk assessment
- approval boards / change advisory boards
- segregation of duties 

## best of both approach

???

# incident management

incident management is a formal process in ITIL, whereas it is a necessary practice in DevOps to handle anomalies in production. as a generalization one might say that ITIL focuses on the incident itself; DevOps, on the other hand, emphasises the learning aspect of unexpected behavior in production. therefore, it could be stated that DevOps relies on resilience engineering: proactive measures to decrease the probability of defects and increase the probability of finding remedies for defects within short time frames. ITIL prescribes a process for handling defects and anomalies but does not really focus on proactive measures (but to be fair ITIL also does not discourage proactive practices).

# some more aspects from real life to make it even more interesting

## COBIT management framework to complicate things
- enterprise governance framework
- strong focus on structure, processes, services, policies, competencies
- top management loves it (for covering their asses)
- integrates well with ITIL (and, therefore, these two together outnumber DevOps in enterprises aiming at combining them all)

## regulatory requirements (applies to highly regulated industry sectors)
- regulators require adherence to standards
- regulators / auditors love COBIT and ITIL
- regulators / auditors value documentation more than knowledge


# interesting references

- https://freshservice.com/itil/itil-versus-devops-blog/
- https://itsm.tools/why-devops-wont-replace-itil/
- https://www.itil.de/2016/11/17/itil-versus-devops-unterschiedliche-sichtweisen/
- https://blog.itil.org/2017/06/itsm-und-devops-freund-oder-feind/
- http://dearauditor.org/
- https://devops.com/integrating-itil-change-management-and-devops/
- https://www.rundeck.com/7-pitfalls-of-incident-management-ebook-rundeck
- https://jaxenter.de/incident-management-devops-keynote-devopscon-2019-livestream-89779
- https://www.youtube.com/watch?v=iiQY9qiDQCE
- https://devops-com.cdn.ampproject.org/c/s/devops.com/devops-versus-itil-how-to-win-the-battle-over-change-management/amp/
- COBIT: https://www.goodelearning.com/courses/it-governance/cobit-foundation/what-is-cobit-5
- EBA guidelines on internal governance: https://eba.europa.eu/regulation-and-policy/internal-governance
