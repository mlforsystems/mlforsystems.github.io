---
title: Overview
---
<div class="inner clearfix">
	<section class="main-content overview_section">
		<h2>Overview</h2>
			<p>Designing specialized hardware for deep learning is a topic that has received significant research attention, both in industrial and academic settings, leading to exponential increases in compute capability in GPUs and accelerators. However, using machine learning to optimize and accelerate software and hardware systems is a lightly explored but promising field, with broad implications for computing as a whole. Very recent work has outlined a broad scope where deep learning vastly outperforms traditional heuristics including topics such as: scheduling<sup>1,2</sup>, data structure design<sup>3</sup>, microarchitecture<sup>4</sup>, compilers<sup>5</sup>, and control of warehouse scale computing systems<sup>6</sup>.
		</p>
		<p>
			The focus of this workshop is to expand upon this recent work and build a community focused on using machine learning in computer systems problems. We seek to improve the state of the art in the areas where learning has already proven to perform better than traditional heuristics, as well as expand to new areas throughout the system stack such as hardware/circuit design and operating/runtime systems.
		</p>
		<p>By forming a community of academic and industrial researchers who are excited about this area, we seek to build towards intelligent, self optimizing systems and answer questions such as: How do we generate and share high quality datasets that span the layers of the system stack? Which learned representations best represent code performance and runtime? Which simulators and simulation methodologies provide a tractable proving ground techniques like reinforcement learning?</p>
		<p>To this end, the target audience for this workshop includes a wide variety of attendees from state-of-the-art researchers in machine learning to domain experts in computer systems design. We have invited a <a href="#speakers">broad set of expert speakers</a> to present the potential for impact of combining deep learning research with computer systems. We hope that by providing a formal venue for researchers from both fields to meet and interact, that the result will include both fundamental research in ML as well as real-world impact to computer systems design and implementation.</p>
		<p>The workshop will host 7 speakers and we will invite researchers to submit relevant papers through our <a href="/call_for_papers.html">call for papers</a>. The speakers, and potentially other relevant stakeholders, will be invited to participate in a panel discussion to end the workshop. See the <a href="/schedule.html">schedule</a> for details.</p>
		<ul class="footnotes">
		<li><sup>1</sup> <a href="https://arxiv.org/abs/1706.04972">Device Placement Optimization with Reinforcement Learning</a></li>
		<li><sup>2</sup> <a href="https://openreview.net/forum?id=Hkc-TeZ0W">A Hierarchical Model for Device Placement</a></li>
		<li><sup>3</sup> <a href="https://arxiv.org/abs/1712.01208">The Case for Learned Index Structures</a></li>
		<li><sup>4</sup> <a href="https://arxiv.org/abs/1803.02329">Learning Memory Access Patterns</a></li>
		<li><sup>5</sup> <a href="https://ieeexplore.ieee.org/document/8091247/?reload=true">End to End Deep Learning of Optimization Heuristics</a></li>
		<li><sup>6</sup> <a href="https://deepmind.com/blog/deepmind-ai-reduces-google-data-centre-cooling-bill-40/">Deepmind AI Reduces Google Data Centre Cooling Bill</a></li>
		<li><sup>7</sup> <a href="https://www.youtube.com/watch?v=YhNl468S8CI">Bayesian optimization for tuning the JVM</a></li>
		<li><sup>8</sup> <a href="https://arxiv.org/abs/1711.11165">Safe Exploration for Identifying Linear Systems via Robust Optimization</a></li>
		</ul>
	</section>
</div>
<div class="speaker_section">
	<div class="inner clearfix">
		<section class="main-content">
			<h2 id="speakers">Speakers</h2>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/jeff_dean.jpg)"></div>
				<div>
					<h3>Jeff Dean</h3>
					<p>
					    Senior Fellow, Google AI. Google Brain lead and co-founder. Co-designer and implementor of Tensorflow, MapReduce, BigTable, Spanner.
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/song_han.jpg)"></div>
				<div>
					<h3>Song Han</h3>
					<p>
					    Song Han is an assistant professor in the Electrical Engineering and Computer Science Department of the Massachusetts Institute of Technology (MIT). Dr. Han received the Ph.D. degree in Electrical Engineering from Stanford University advised by Prof. Bill Dally. Dr. Han co-founded DeePhi Tech in 2016, a startup offering efficient solutions for deep learning computing (deep compression and hardware acceleration).
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/sanjay_krishnan.png)"></div>
				<div>
					<h3>Sanjay Krishnan</h3>
					<p>
					    Assistant Professor of Computer Science at the University of Chicago.
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/partha_ranganathan.jpg)"></div>
				<div>
					<h3>Partha Ranganathan</h3>
					<p>
					    Parthasarathy (Partha) Ranganathan is currently at Google designing their next-generation systems. Before this, he was a HP Fellow and Chief Technologist at Hewlett Packard Labs where he led their research on systems and datacenters. Dr. Ranganathan's research interests are in systems architecture and manageability, energy-efficiency, and systems modeling and evaluation. He has done extensive work in these areas including key contributions around energy-aware user interfaces, heterogeneous multi-core processors, power capping and power-aware server designs, federated enterprise power management, energy modeling and benchmarking, disaggregated blade server architectures, and most recently, storage hierarchy and systems redesign for non-volatile memory. He was also one of the primary developers of the publicly distributed Rice Simulator for ILP Multiprocessors (RSIM).
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/eric_schkufza.jpg)"></div>
				<div>
					<h3>Eric Schkufza</h3>
					<p>
					    Researcher at VMWare applying data analysis and machine learning to the design of optimizing compilers. His work focuses on optimization of low-level machine code in the absence of its original source, and FPGA development.
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/oriol_vinyals.jpg)"></div>
				<div>
					<h3>Oriol Vinyals</h3>
					<p>
					    Oriol Vinyals is a Research Scientist at Google DeepMind, working in Deep Learning. Prior to joining DeepMind, Oriol was part of the Google Brain team. He holds a Ph.D. in EECS from University of California, Berkeley and is a recipient of the 2016 MIT TR35 innovator award. His research has been featured multiple times at the New York Times, BBC, etc., and his articles have been cited over 17000 times. His academic involvement includes program chair for the International Conference on Learning Representations (ICLR) of 2017, and 2018. He has also been an area chair for many editions of the NIPS and ICML conferences. At DeepMind he continues working on his areas of interest, which include artificial intelligence, with particular emphasis on machine learning, deep learning and reinforcement learning.
					</p>
				</div>
			</div>
			<div class="speaker-bio">
				<div class="img-holder" style="background-image: url(/assets/images/speakers/neeraja_yadwadkar.jpg)"></div>
				<div>
					<h3>Neeraja J. Yadwadkar</h3>
					<p>
					    Neeraja recently graduated with a PhD in Computer Science from University of California, Berkeley. Her thesis was on automatic resource management in the datacenter and the cloud. She is now a post-doctoral researcher in the Computer Science Department at Stanford University where she continues to work on distributed systems, cloud computing, and machine learning.
					</p>
				</div>
			</div>
		</section>
	</div>
</div>
<div class="organizers-section">
	<div class="inner clearfix">
		<section class="main-content">
			<h2>Organizing Committee</h2>
			<ul>
				<li><b>Anna Goldie</b>, Google Brain, <a href="https://twitter.com/annadgoldie">@annadgoldie</a></li>
				<li><b>Azalia Mirhoseini</b>, Google Brain, <a href="https://twitter.com/Azaliamirh">@Azaliamirh</a></li>
				<li><b>Jonathan Raiman</b>, OpenAI, <a href="https://twitter.com/jonathanrraiman">@jonathanrraiman</a></li>
				<li><b>Kevin Swersky</b>, Google Brain, <a href="https://twitter.com/kswersk">@kswersk</a></li>
				<li><b>Milad Hashemi</b>, Google, <a href="https://hps.ece.utexas.edu/people/miladh/">website</a></li>
			</ul>
			<h2>Program Committee</h2>
			<ul>
				<li><b>Anna Goldie</b>, Google Brain</li>
				<li><b>Azalia Mirhoseini</b>, Google Brain</li>
				<li><b>Jonathan Raiman</b>, OpenAI</li>
				<li><b>Kevin Swersky</b>, Google Brain</li>
				<li><b>Milad Hashemi</b>, Google</li>
				<li><b>Simon Kornblith</b>, Google</li>
				<li><b>Nicholas Frosst</b>, Google</li>
				<li><b>Zhan Shi</b>, University of Texas at Austin</li>
				<li><b>Will Hang</b>, Stanford</li>
				<li><b>Amir Yazdanbakhsh</b>, Google</li>
				<li><b>Azade Nazi</b>, Google</li>
				<li><b>Alex Ray</b>, OpenAI</li>
				<li><b>Andrew Gibiansky</b>, Voicery</li>
				<li><b>James Bradbury</b>, Google</li>
				<li><b>Sharan Narang</b>, Google Brain</li>
				<li><b>Martin Maas</b>, Google</li>
				<li><b>Carlos Villavieja</b>, Google</li>
			</ul>
			<h2>Contact Us</h2>
			<p>
				Contact us at <a href="mailto:mlforsystems@googlegroups.com">mlforsystems@googlegroups.com</a>.
			</p>
		</section>
</div>
