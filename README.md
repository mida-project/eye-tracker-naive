# Eye Tracker Naïve Solution

<img src="https://www.groovypost.com/wp-content/uploads/2017/08/Tobii-Eye-Tracker.png" width="100%" />

From an [early setup experiment](https://github.com/mida-project/eye-tracker-setup), we developed this [repository](https://github.com/mida-project/eye-tracker-naive). The repository is a naïve approach to measure and calculate the setup of [Tobii Eye Tracker 4C](https://gaming.tobii.com/product/tobii-eye-tracker-4c/) gazing information for [usability testing](https://github.com/MIMBCD-UI/prototype-breast-screening/wiki/User-Research#user-test-evaluations-) purpose. The [Tobii Eye Tracker 4C](https://gaming.tobii.com/product/tobii-eye-tracker-4c/) aims at providing an immersive reality without an headset. Also, with this product nothing stands between the screen and the immersive experience. Therefore, our clinicians will work with no interference of the device. This repository includes software from the [GazeTrack: Eye-tracking for Processing (Tobii EyeX and 4C)](http://hci.soc.napier.ac.uk/GazeTrack/) library developed by [Augusto Esteves](http://hci.soc.napier.ac.uk/) for the [Processing](http://www.processing.org/) programming environment. It is also available on [GitHub](https://github.com/AugustoEst/gazetrack). The [GazeTrack](http://hci.soc.napier.ac.uk/GazeTrack/) is a library that supports basic gaze tracking for our [Tobii Eye Tracker 4C](https://gaming.tobii.com/product/tobii-eye-tracker-4c/) device. The repository is part of the work done by [SIPg](http://sipg.isr.tecnico.ulisboa.pt/), an [ISR-Lisboa](http://welcome.isr.tecnico.ulisboa.pt/) research group and [M-ITI](https://www.m-iti.org/), two [R&D Units](http://larsys.pt/index.php/facilities/) of [LARSyS](http://larsys.pt/). The project also involves the collaborative effort of [INESC-ID](http://www.inesc-id.pt/). Both [ISR-Lisboa](http://welcome.isr.tecnico.ulisboa.pt/) and [INESC-ID](http://www.inesc-id.pt/) are [Associate Laboratories](https://tecnico.ulisboa.pt/en/research-and-innovation/rd/associate-laboratories/) of [IST](http://tecnico.ulisboa.pt/) from [ULisboa](https://www.ulisboa.pt/).

## Pre-Requisites

The following list is showing the set of dependencies for this project. Please, install and build the recommended versions in your machine.

List of dependencies and recommended versions for this repository:

- [Git](https://git-scm.com/) (>= [v2.20](https://raw.githubusercontent.com/git/git/master/Documentation/RelNotes/2.20.1.txt))

- [Windows 10](https://www.microsoft.com/pt-pt/software-download/windows10) (>= [v1809](https://docs.microsoft.com/en-us/windows/windows-10/release-information))

- [Processing](http://www.processing.org/) (>= [v3.5.3](https://github.com/processing/processing/releases/tag/processing-0269-3.5.3))

- [TobiiStream](http://hci.soc.napier.ac.uk/GazeTrack/TobiiStream.zip) (>= [v2.0.3](http://hci.soc.napier.ac.uk/GazeTrack/download/GazeTrack-2.zip))

### Analytical Use

Tobii’s consumer eye trackers are primarily intended for personal interaction use and not for analytical purposes. Any application that stores or transfers eye tracking data must have a special license from Tobii ([Read more](https://analyticaluse.tobii.com/)). Please, apply for a license [here](https://analyticaluse.tobii.com/license-application-form/).

## Instructions

The instructions are as follows. We assume that you already have knowledge over [Git](https://git-scm.com/) and [GitHub](https://github.com/). If not, please follow this [support](https://guides.github.com/activities/hello-world/) information. Any need for support, just open a [New issue](https://github.com/mida-project/eye-tracker-naive/issues/new).

### Clone

To clone the hereby repository follow the guidelines. It is easy as that.

1.1. Please clone the repository by typing the command:

```
git clone https://github.com/mida-project/eye-tracker-naive.git
```

1.2. Get inside of the repository directory:

```
cd eye-tracker-naive/
```

1.3. For the installation and running of the source code, follow the next steps;

### Run

The running guidelines are as follows. Please, be sure that you follow it correctly.

2.1. Run the sample using the following command:

```
TobiiStream\TobiiStream.exe > samples\test_3.txt
```

2.2. Now open the [`samples/`](samples/) directory and observe the `test_3.txt` file;

2.3. Enjoy our source code!

## Information

We developed this [repository](https://github.com/mida-project/eye-tracker-naive) as a naïve and lazy approach from failing to implement [an early, yet complete, solution](https://github.com/mida-project/eye-tracker-setup) for our problem. This happens "thanks" to the high availability (**NOT**) of Tobii's team to provide us (sarcasm, sarcasm and more sarcasm) a license for our study. If you still want to find out how to apply the [Upgrade Key](https://www.tobiipro.com/siteassets/tobii-pro/product-descriptions/tobii-pro-upgrade-key-product-description.pdf/?v=1.5) (advice: you are losing your time) to a [Tobii Eye Tracker 4C](https://gaming.tobii.com/product/tobii-eye-tracker-4c/), follow the [Tobii Pro Upgrade Key – User Instructions](https://www.tobiipro.com/siteassets/tobii-pro/user-manuals/tobii-pro-upgrade-key-user-instructions.pdf/?v=1.1) document. From there, and if you have any luck, you can try back [our old solution](https://github.com/mida-project/eye-tracker-setup). Nevertheless, you can follow the presented steps. Any questions regarding the [Eye-Tracking topic](https://en.wikipedia.org/wiki/Eye_tracking) just follow the [StackOverflow tag](https://stackoverflow.com/questions/tagged/eye-tracking) for the purpose.

On the next animation, we present a potential Use Case for our future [User Tests](https://github.com/MIMBCD-UI/prototype-breast-screening/wiki/User-Research#test-7-multi-modality-vs-assistant-chi2020-). In this tests, we aim to apply the [Eye Tracking technique](https://link.springer.com/chapter/10.1007/978-1-4471-3750-4_5) across several [Medical Imaging (MI)](https://en.wikipedia.org/wiki/Medical_imaging) technologies to understand gaze behaviour of the clinicians. A sample of a gaze output can be seen below.

<img src="assets/breast_2.gif" width="100%" />

Sample of gaze output:

```
TobiiStream v2.0.3

SUCCESS: The connection to the GazeTrack Processing library has been correctly set up!

TobiiState Present
TobiiStream 4964391.9978 1409.01264816592 1490.13762876426
TobiiStream 4964403.5532 1412.13326149614 1491.61791154857
TobiiStream 4964414.6863 1413.14194231297 1492.55350841627
TobiiStream 4964425.2119 1412.89475257191 1492.45911056297
TobiiStream 4964436.7849 1414.89398222908 1491.08490976601
TobiiStream 4964447.8616 1415.72645020609 1490.97596126832
TobiiStream 4964458.7331 1398.7559159215 1487.89992585501
```

### Acknowledgements

The work is also based and higly contributed from the [`gazetrack`](https://github.com/AugustoEst/gazetrack) repository. The [`gazetrack`](https://github.com/AugustoEst/gazetrack) repository was developed by [Augusto Esteves](http://hci.soc.napier.ac.uk/) ([AugustoEst](https://github.com/AugustoEst)) that we would like to thank. That repository shows pretty much everything we need to collect information from a [Tobii Eye-Tracker](https://gaming.tobii.com/products/), get gaze coordinates and time synchronization data.

### Authors

- [Francisco Maria Calisto](http://www.franciscocalisto.me/) [[ResearchGate](https://www.researchgate.net/profile/Francisco_Maria_Calisto) | [GitHub](https://github.com/FMCalisto) | [Twitter](https://twitter.com/FMCalisto) | [LinkedIn](https://www.linkedin.com/in/fmcalisto/)]

## Sponsors

<span class="image">
  <a href="http://www.fct.pt/" title="FCT" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fct_footer.png?raw=true" alt="fct" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.fccn.pt/en/" title="FCCN" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/fccn_footer.png?raw=true" alt="fccn" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.ulisboa.pt/en/" title="ULisboa" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ulisboa_footer.png?raw=true" alt="ulisboa" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://tecnico.ulisboa.pt/" title="IST" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/ist_footer.png?raw=true" alt="ist" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://hff.min-saude.pt/" title="HFF" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/hff_footer.png?raw=true" alt="hff" width="20%" />
  </a>
</span>

## Departments

<span class="image">
  <a href="http://dei.tecnico.ulisboa.pt" title="DEI" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/dei_footer.png?raw=true" alt="dei" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://deec.tecnico.ulisboa.pt" title="DEEC" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/deec_footer.png?raw=true" alt="dei" width="20%" />
  </a>
</span>

## Laboratories

<span class="image">
  <a href="http://sipg.isr.tecnico.ulisboa.pt/" title="SIPG" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/sipg_footer.png?raw=true" alt="sipg" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://welcome.isr.tecnico.ulisboa.pt/" title="ISR" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/isr-lisboa_footer.png?raw=true" alt="isr" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://larsys.pt/" title="LARSys" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/larsys_footer.png?raw=true" alt="larsys" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.m-iti.org/" title="M-ITI" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/miti_footer.png?raw=true" alt="inesc-id" width="20%" />
  </a>
</span>
<span class="image">
  <a href="http://www.inesc-id.pt/" title="INESC-ID" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/inesc-id_footer.png?raw=true" alt="inesc-id" width="20%" />
  </a>
</span>

## Domain

<span class="image">
  <a href="https://europa.eu/" title="EU" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/eu_footer.png?raw=true" alt="eu" width="20%" />
  </a>
</span>
<span class="image">
  <a href="https://www.portugal.gov.pt/" title="Portugal" target="_blank">
    <img src="https://github.com/mida-project/meta/blob/master/brands/pt_footer.png?raw=true" alt="pt" width="20%" />
  </a>
</span>