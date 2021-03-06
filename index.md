**!! Create and view submissions at the [EfficientQA leaderboard](https://ai.google.com/research/NaturalQuestions/efficientqa). !!**

Open domain question answering is emerging as a benchmark method of measuring
computational systems' abilities to read, represent, and retrieve knowledge
expressed in all of the documents on the web.

In this competition contestants will develop a question answering system that
contains all of the knowledge required to answer open-domain questions. There
are no constraints on how the knowledge is stored---it could be in documents,
databases, the parameters of a neural network, or any other form. However, three
competition tracks encourage systems that store and access this knowledge using
the smallest number of bytes, including code, corpora, and model
parameters. There will also be an unconstrained track, in which the goal is to
achieve the best possible question answering performance with no
constraints. The best performing systems from each of the tracks will be put to
test in a live competition against trivia experts during the [NeurIPS 2020
competition track](https://neurips.cc/Conferences/2020/CompetitionTrack).

All submissions to the *memory constrained* tracks must be made to the
[EfficientQA leaderboard](https://ai.google.com/research/NaturalQuestions/efficientqa)
before 2020/11/14. Once the leaderboard is closed, the test set inputs will 
be released and participants will be given until the end of 2020/11/17 to submit
predictions to the *unconstrained* track. To recieve notifications regarding this
process,  please
[sign up to our mailing list](https://efficientqa.github.io/sign_up_for_notifications.html).

We have provided
[tutorials on baseline systems](https://efficientqa.github.io/getting_started.html)
as well as a complete
[guide to making a submission](https://efficientqa.github.io/getting_started.html).
If you have any questions, please
[create an issue in this repository](https://github.com/efficientqa/efficientqa.github.io/issues).

## Competition Overview

This competition will be evaluated using the open domain variant of the
[*Natural Questions*](https://www.mitpressjournals.org/doi/full/10.1162/tacl_a_00276)
question answering task. The questions in *Natural Questions* are real Google
search queries, and each is paired with up to five reference answers. The
challenge is to build a question answering system that can generate a correct
answer given just a question as input.

### Competition Tracks

This competition has four separate tracks. In the *unrestricted* track
contestants are allowed to use arbitrary technology to answer questions, and
submissions will be ranked according to the accuracy of their predictions alone.

There are also three *restricted* tracks in which contestants will have to
upload their systems to our servers, where they will be run in a sandboxed
environment, without access to any external resources. In these three tracks,
the goal is to build:

* the most accurate self-contained question answering system under 6Gb,
* the most accurate self-contained question answering system under 500Mb,
* the smallest self-contained question answering system that achieves 25%
  accuracy.

More information on the task definition, data, and evaluation can be found
[here](https://efficientqa.github.io/task_definition.html).

### Competition prizes
Each of the *restricted* tracks comes with a prize of approximately $3000
in Google Cloud credits. Each submitter can win at most one track. Please 
go to the leaderboard site for full
[terms and conditions](https://ai.google.com/research/NaturalQuestions/efficientqa/termsAndConditions).

### Human Evaluation

In practice, five reference answers are sometimes not enough---there are a lot
of ways in which an answer can be phrased, and sometimes there are multiple
valid answers. At the end of this competition's submission period, predictions from the
best performing systems will be checked by humans. This human evaluation will be used
to calculate an alternate ranking, which will be presented along with the automatic 
leaderboard rank at NeurIPS 2020.

## Baseline Systems
We have provided a tutorial for getting started with
several baseline systems that either generate answers directly, from a neural network,
or extract them from a corpus of text. You can find the tutorial
[here](https://efficientqa.github.io/getting_started.html).

## Important Dates

|                                 |                                                                   |
|:--------------------------------|:------------------------------------------------------------------|
| **September 14, 2020**          | Leaderboard launched.                                             |
| **November 14, 2020**           | Leaderboard frozen.                                               |
| **November 30, 2020**           | Human evaluation completed and results announced.                 |
| **December 11-12, 2020** &emsp; | NeurIPS workshop and human-computer competition (held virtually). |

## Organizers

*   [Adam Roberts](https://research.google/people/104881/), Google
    Research
*   [Chris Alberti](https://research.google/people/ChrisAlberti/),
    Google Research
*   [Colin Raffel](https://colinraffel.com/), Google Research / University of
    North Carolina
*   [Danqi Chen](https://www.cs.princeton.edu/~danqic/), Princeton University
*   [Eunsol Choi](https://www.cs.utexas.edu/~eunsol/), Google Research / UT
    Austin
*   [Hannaneh Hajishirzi](https://homes.cs.washington.edu/~hannaneh/),
    University of Washington
*   [Jennimaria Palomaki](https://research.google/people/105807/),
    Google Research
*   [Jordan Boyd-Graber](http://users.umiacs.umd.edu/~jbg/), University of
    Maryland
*   [Kelvin Guu](http://kelvinguu.com/), Google Research
*   [Kenton Lee](https://kentonl.com/), Google Research
*   [Michael Collins](https://research.google/people/MichaelCollins/),
    Google Research
*   [Sewon Min](https://shmsw25.github.io/), University of Washington
*   [Tom Kwiatkowski](https://research.google/people/105075/), Google
    Research

## Contact

Please contact `efficientqa@googlegroups.com` with any questions.
