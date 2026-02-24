

<img src="https://drive.google.com/uc?id=1KPIYlaN68vlL99iApaF5QbeBoyT24-Eu">

import numpy as np

!pip install --upgrade gdown




!gdown 1c0ClC8SrPwJq5rrkyMKyPn80nyHcFikK

score = np.loadtxt('survey.txt', dtype ='int')

score

len(score)

detractors = score[score <= 6]

detractors

len(detractors)

332/1167

promoters = score[score >= 9]

promoters

len(promoters)

609/1167

52-28

