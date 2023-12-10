---
title: Announcement
workshop_name: neurips2023
site_description: Workshop on ML for Systems at NeurIPS 2023, December, New Orleans
mini_site_description: Workshop on ML for Systems at NeurIPS '23, Dec
site_title: ML For Systems
---

<div class="speaker_section">
  <div class="inner clearfix">
    <section class="main-content">
      <h2 id="speakers">Speakers</h2>
	    <div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/chris_lattner.jpeg)"></div>
				<div>
					<h3 class="keynote-speaker">Keynote: Programming Languages Challenges in Large Scale Machine Learning</h3>
					<h4>Chris Lattner (Modular.ai)</h4>
					<p>
                        Chris is the co-founder and CEO of Modular AI. He cofounded the LLVM Compiler infrastructure, the Clang compiler, the Swift programming language, the MLIR compiler infrastructure, the CIRCT project (applying MLIR to hardware design), and have contributed to many other commercial and open source projects at Apple, Tesla, Google, and SiFive. Previously, Chris led the Engineering and Product teams at SiFive, the Google TensorFlow team, the Tesla Autopilot team, and worked for Apple managing the Developer Tools department.
					</p>
				</div>
        </div>
    	<div class="speaker-bio">
			<div class="img-holder" style="background-image: url(/assets/images/speakers/bill_dally.jpeg)"></div>
				<div>
					<h3 class="talk-speaker">Special Speaker: Adapting Large Language Models for Chip Design at NVIDIA</h3>
					<h4>William Dally (NVIDIA)</h4>
					<p>
					    Dr. William "Bill" Dally is a computer architecture pioneer with extensive experience in circuit design, high performance computing, and machine learning. In 2009, Dally joined NVIDIA as the chief scientist, where he is currently the SVP of Research. Previously, Dally led research teams at Stanford for 12 years and MIT for 11 years as a professor, and he co-founded two companies. e is a member of the National Academy of Engineering, a Fellow of the American Academy of Arts & Sciences, a Fellow of the IEEE and the ACM, and has received the ACM Eckert-Mauchly Award, the IEEE Seymour Cray Award, and the ACM Maurice Wilkes award. He has published over 250 papers, holds over 120 issued patents, and is an author of four textbooks. His work can be seen in most large parallel computers today.
					</p>
				</div>
        </div>
        <div class="speaker-bio">
                <div class="img-holder" style="background-image: url(/assets/images/speakers/atlas_wang.jpg)"></div>
				<div>
					<h3 class="talk-speaker">Leveraging Sparsity for Efficient Training, Inference, and Transfer</h3>
					<h4>Atlas Wang (The University of Texas at Austin)</h4>
					<p>Professor Zhangyang "Atlas" Wang is an associate professor at UT Austin, where he holds the Temple Foundation Endowed Faculty Fellowship #7, in the Chandra Family Department of Electrical and Computer Engineering. He is also a faculty member of UT Computer Science (GSC) and the Oden Institute CSEM program. Wang directs AI Research and Technology at Picsart part time.  Wang is a recipient of numerous awards, including NSF CAREER, IEEE AI's 10 To Watch, and Google Research Scholar awards.
					</p>
				</div>
        </div>
<div class="inner clearfix">
	<section class="main-content overview_section">
		<h2>What To Expect</h2>
        <p>The ML for Systems workshop presents cutting-edge work on ML in computer systems and aims to develop a unified methodology for the field.
        </p>
        <p>Machine Learning (ML) for Systems describes the application of machine learning techniques to problems related to computer systems. By leveraging supervised learning and reinforcement learning (RL) approaches, machine learning can replace longstanding heuristics that currently drive many of these systems. This includes a wide range of topics, including multi-objective tasks such as designing new data structures <sup><a href="https://arxiv.org/abs/1706.04972">1</a></sup>, integrated circuits <sup><a href="https://openreview.net/forum?id=Hkc-TeZ0W">2</a>, <a href="https://arxiv.org/abs/1712.01208">3</a></sup>, or design verification <sup><a href="https://dvcon-proceedings.org/wp-content/uploads/Adaptive-Test-Generation-for-Fast-Functional-Coverage-Closure.pdf">20</a>, <a href="https://dvcon-proceedings.org/wp-content/uploads/Test-Parameter-Tuning-with-Blackbox-Optimization-A-Simple-Yet-Effective-Way-to-Improve-Coverage-1.pdf">21</a></sup>, as well as implementing control algorithms for applications such as compilers <sup><a href="https://arxiv.org/abs/1805.03441">12</a>, <a href="https://arxiv.org/abs/1805.08166">13</a>, <a href="https://arxiv.org/abs/2011.14486">19</a></sup>, databases <sup><a href="https://arxiv.org/abs/1711.11165">8</a></sup>, memory management <sup><a href="https://arxiv.org/abs/1803.02329">9</a>, <a href="https://research.google/pubs/pub49008/">10</a></sup>, or ML frameworks <sup><a href="https://arxiv.org/abs/1906.08879">11</a></sup>. While the systems community increasingly recognizes the importance of ML in solving a variety of different systems problems <sup><a href="https://www.sigarch.org/5-guidelines-for-research-in-ml-for-systems/">23</a></sup>, ML for Systems remains an emerging area without widely established best practices, methods and strategies for the application of state-of-the-art machine learning techniques <sup><a href="https://ieeexplore.ieee.org/document/9153088">22</a></sup>. The goal of this workshop is to provide an interdisciplinary venue for ML and Systems experts to push this boundary and start new directions within the ML for Systems area.
        </p>
        <h3>Workshop Direction</h3>
        <p>
        In previous 6 editions, we showcased specific approaches and frameworks to solve problems, bringing together researchers and practitioners at NeurIPS from both the ML and systems communities. While breaking new grounds, we encouraged collaborations and development in a broad range of ML for Systems works, many later published in top-tier conferences <sup><a href="https://arxiv.org/abs/1906.08879">11</a>, <a href="https://arxiv.org/abs/1805.08166">13</a>, <a href="https://arxiv.org/abs/1810.01963">14</a>, <a href="https://arxiv.org/abs/1811.01704">15</a>, <a href="https://arxiv.org/abs/1808.07412">16</a>, <a href="https://arxiv.org/abs/2104.04955">17</a>, <a href="https://dl.acm.org/doi/10.1145/3439706.3447045">18</a></sup>. This year, we plan to continue this path while encouraging work in key emerging areas such as Large Language Model (LLM) training and serving, and unifying benchmarks on key problems such as scheduling and compiling through a competition.
        </p>
        <p>Recently, the rise of Large Language Models (LLMs) has presented new opportunities and challenges within the domain of computer systems. Our community is well-positioned to produce science and stimulate discussion for adapting to the new paradigm, especially how LLMs can be used to solve systems problems, and using ML to address systems issues that emerge from LLM training and serving. Additionally, as the field matures, we emphasize on keeping the research open, and the science reproducible. To that end, we are supplementing our main program with a competition track to crystallize the field’s progress.
        </p>
        <h3>Workshop Goals </h3>
        <p>NeurIPS provides a unique opportunity to bring together systems researchers and researchers from other sub-areas of ML who had not previously considered applying their techniques in a computer systems context. We see the goal of our workshop as solving the following two objectives:
        <ul>
            <li>Opening up connections between research areas that were not previously considered, connecting the ML and Systems communities, growing the scope of ML for Systems work and unlocking new research opportunities.</li>
            <li>Developing best practices, methodologies and benchmarks for the ML for Systems field.</li>
        </ul>
        </p>
        <p>To build commonalities on the topic of LLMs interacting with computational systems, we specifically include seminal talks on emerging trends on training and serving LLMs from seasoned researchers and practitioners as a part of our invited speakers. Our call for papers also includes topics at the intersection of Systems and LLMs.
        </p>
        <h2>Competition Track</h2>
        <p>This year, we introduced an auxiliary competition track to showcase state-of-the-art capabilities under open benchmarks. We hoped that the first iteration of the competition will serve as an initiative to encourage industrial sharing ML for systems data.</p>
        <p>Our <a href="https://www.kaggle.com/competitions/predict-ai-model-runtime">Kaggle competition</a> on ML model runtime prediction just completed, with 792 participants on 616 teams! We received a total of 10,507 submission entries from 66 countries. The solutions from the competitors cover an impressive range of models and feature transformations, which yield impressive gains over our baseline model. Thank you all for participating in this competition and congratulations to the winners!</p>
    <h2>Call for Papers</h2>
    <p>We invite researchers to submit relevant papers through our <a href="/call_for_papers.html">call for papers</a>. Our program include contributed speakers and poster sessions from selected works.</p>
    <!--h2>Camera-Ready Instructions</h2>
        <p>For accepted papers, please update the camera-ready manuscript on OpenReview by <b>November 17th AoE</b>.</p>
        <p>Please see instructions below:
            <ul>
                <li>The camera-ready template is the same as the one used for submission, which is same as NeurIPS papers. Kindly use the Final package. We have made some minor changes to the format. Please use <a href="/assets/latex/MLforSysLatexFiles.zip"><b>the template (.zip)</b></a></li> attached.
                <li>There is a hard page limit of 4 pages (excluding references and Appendix).</li>
                <li>Appendix and references do not have a limit</li>
            </ul>
        </p-->
    <!--h2>Competition Track (<b>NOW LIVE</b>)</h2>
    <p>We introduce an auxiliary competition track to showcase state-of-the-art capabilities under open benchmarks. The first iteration serves as an initiative to encourage industrial sharing ML for systems data, with the tentative topic on <b>predicting program runtime from XLA graphs</b>.</p>
    <p> The top winners have the opportunities to share their technical reports to receive sponsor prizes.</p>
    <p>The ML for Systems dataset and benchmarks for Runtime Prediction is now live at <a href="https://www.kaggle.com/competitions/predict-ai-model-runtime">Kaggle</a>.</p-->
	</section>
</div>
<div class="organizers-section">
	<div class="inner clearfix">
		<section class="main-content">
			<h2>Organizing Committee</h2>
			<ul>
				<li><b>Mimee Xu</b>, NYU, <a href="https://twitter.com/MimeeXu">@MimeeXu</a></li>
                <li><b>Dan Zhang</b>, Google DeepMind, <a href="https://www.linkedin.com/in/danzhang3">LinkedIn</a></li>
                <li><b>Phitchaya Mangpo Phothilimthana</b>, Google DeepMind, <a href="https://www.linkedin.com/in/phitchaya-mangpo-phothilimthana">LinkedIn</a></li>
                <li><b>Beidi Chen</b>, CMU, <a href="https://twitter.com/BeidiChen">@BeidiChen</a></li>
                <li><b>Yawen Wang</b>, Google SystemsResearch, <a href="https://www.linkedin.com/in/yawen-wang-589b38113">@LinkedIn</a></li>
                <li><b>Divya Mahajan</b>, Microsoft Research and Georgia Tech. <a href="https://twitter.com/divyamahajn">@DivyaMahajn</a></li>
			</ul>
            <h2>Competition Committee</h2>
			<ul>
                <li><b>Bryan Perozzi</b>, Google Research, <a href="https://twitter.com/phanein">@phanein</a></li>
                <li><b>Phitchaya Mangpo Phothilimthana</b>, Google DeepMind, <a href="https://www.linkedin.com/in/phitchaya-mangpo-phothilimthana-64415b82">LinkedIn</a></li>
                <li><b>Sami Abu-el-haija</b>, Google Research, <a href="https://twitter.com/abu_usc">@abu_usc</a></li>
            </ul>
            <h2>Steering Committee</h2>
			<ul>
                <li><b>Martin Maas</b>, Google DeepMind, <a href="https://twitter.com/martin_maas">@martin_maas</a></li>
                <li><b>Jonathan Raiman</b>, NVIDIA, <a href="https://twitter.com/jonathanrraiman">@jonathanrraiman</a></li>
                <li><b>Anna Goldie</b>, Anthropic, <a href="https://twitter.com/annadgoldie">@annadgoldie</a></li>
                <li><b>Azalia Mirhoseini</b>, Anthropic, <a href="https://twitter.com/Azaliamirh">@Azaliamirh</a></li>
				<li><b>Milad Hashemi</b>, Google, <a href="https://twitter.com/miladhash">@miladhash</a></li>
				<li><b>Kevin Swersky</b>, Google, <a href="https://twitter.com/kswersk">@kswersk</a></li>
			</ul>
            <h2>Contact Us</h2>
            <p>
                Contact us at <a href="mailto:mlforsystems@googlegroups.com">mlforsystems@googlegroups.com</a>.
            </p>
		</section>
</div>