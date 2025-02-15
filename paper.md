<img src="&#39;./images/&#39;/media/image1.png"
style="width:8.38889in;height:0.69375in" />

> Highlights of CMU Research on
>
> CAD, CAM and CAT of VLSI Circuits

<img src="&#39;./images/&#39;/media/image2.jpeg"
style="width:8.25in;height:0.34028in" />

John Paul Shen

<img src="&#39;./images/&#39;/media/image3.jpeg"
style="width:8.25in;height:0.34028in" />

> SRC-CMU Research Center for Computer-Aided Design
>
> Department of Electrical and Computer Engineering
>
> Carnegie Mellon University

<img src="&#39;./images/&#39;/media/image4.jpeg"
style="width:8.25in;height:0.34028in" />

> Schenley Park, Pittsburgh, PA 15213

<img src="&#39;./images/&#39;/media/image5.jpeg"
style="width:8.25in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image6.png"
style="width:8.25in;height:2.04028in" />

1.  OVERVIEW

<img src="&#39;./images/&#39;/media/image7.jpeg"
style="width:8.25in;height:0.34028in" />

> Three disciplines are involved in the realization of a

<img src="&#39;./images/&#39;/media/image8.jpeg"
style="width:8.25in;height:0.34028in" />

> VLSI circuit: design, manufacture, and test. Each of these
>
> disciplines involves a number of activities and requires the
>
> use of various computer aids. Because Computer-Aided

<img src="&#39;./images/&#39;/media/image9.jpeg"
style="width:8.25in;height:0.34028in" />

> Design (CAD), Computer-Aided Manufacture (CAM), and
>
> Computer-Aided Test (CAT) traditionally have been viewed

<img src="&#39;./images/&#39;/media/image10.jpeg"
style="width:8.25in;height:0.34028in" />

> as separate disciplines, the aids that have been developed for
>
> them are by and large unrelated and noninteractive. In our

<img src="&#39;./images/&#39;/media/image11.jpeg"
style="width:8.25in;height:0.34028in" />

> view, it is essential that an integrated approach be used for
>
> the design and implementation of computer aids for these three
> disciplines.

<img src="&#39;./images/&#39;/media/image12.jpeg"
style="width:8.25in;height:0.34028in" />

> Taking into account the fabrication process, four major

<img src="&#39;./images/&#39;/media/image13.jpeg"
style="width:8.25in;height:0.34028in" />

> steps are involved in the realization of a VLSI circuit chip,
>
> namely process design, circuit design, nanufacture and test.
>
> Traditionally CAD tools are used to speed up the circuit design step
> and CAT tools are used during the test step to

<img src="&#39;./images/&#39;/media/image14.jpeg"
style="width:8.25in;height:0.34028in" />

> guarantee circuit performance. The SRC-CMU research

<img src="&#39;./images/&#39;/media/image15.jpeg"
style="width:8.25in;height:0.34028in" />

> center for CAD has a broad-based program aimed at
>
> developing an integrated approach to CAD, CAM and CAT.

<img src="&#39;./images/&#39;/media/image16.jpeg"
style="width:8.25in;height:0.34028in" />

> Our first step towards this integration involves the concepts
>
> of manufacturing-based CAD and manufacturing-based
>
> CAT; see Figure 1. Manufacturing-based CAD supports

<img src="&#39;./images/&#39;/media/image17.jpeg"
style="width:8.25in;height:0.34028in" />

> both process design and circuit design with the aim of
>
> achieving short design time, fast turn-around and high

<img src="&#39;./images/&#39;/media/image18.jpeg"
style="width:8.25in;height:0.34028in" />

> manufacturing yield. Manufacturing-based CAT utilizes
>
> technology and process information to effect accurate

<img src="&#39;./images/&#39;/media/image19.jpeg"
style="width:8.25in;height:0.34028in" />

> screening of defective chips during fabrication test.

<img src="&#39;./images/&#39;/media/image20.jpeg"
style="width:8.25in;height:0.34028in" />

> Figure 1. Integrated CAD/CAM/CAT - First Step.
>
> Currently, the center has approximately forty ongoing

projects, which are loosely grouped into the following areas:

1.  Design

<!-- -->

1.  Synthesis

> 0 Verification
>
> 0 Simulation

1.  Manufacturing l Testing

> lDesignEnvironment

A representative, though not comprehensive, set of projects

is described in this paper. Some projects are described in

more detail to highlight recent results and future directions. This
paper represents an abridged and updated version of an earlier paper
\[l\]. Only a sample of references appears in this

paper; a comprehensive list of references can be found in \[l\].

878

CH2345-7/86/0000/0878$01.00@ 1986 IEEE

1.  DESIGN

> The goal of our CAD research is to develop a design automation system
> that involves a design methodology and a supporting set of computer
> aids that can take a behavioral description of the desired VLSI
> circuit, a description of the target technology, and a set of
> constraints, and then produce a set of masks that could be used to
> fabricate the circuit. The design produced should be testable and
> comparable in cost, speed, and reliability with manually produced
> designs.
>
> Availability of such a design automation system would
>
> significantly reduce the time required to design a VLSI system as well
> as produce designs which are correct the first
>
> time and manufacturable with acceptable yield. Figure 2 illustrates
> this overall objective.

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

Manu

> Figure 2. CAD Research Objective.
>
> Our research activities have been aimed at developing new techniques
> to aid in a wide range of CAD tasks, and can be categorized around
> several main thrusts which include:
>
> l An investigation into the use of Knowledge-Based Expert Systems
> (KBES) as an aid in synthesis and analysis.
>
> l Development of top-down synthesis methods at the system and physical
> design levels which can make use of bottom-up information.
>
> l Development of simulation tools to span all levels of the hierarchy.

<img src="&#39;./images/&#39;/media/image21.png"
style="width:8.27778in;height:0.67361in" />

> l Development of a consistent multilevel
>
> representation to provide a means for our programs to communicate and
> as a basis for

<img src="&#39;./images/&#39;/media/image22.jpeg"
style="width:8.27778in;height:0.33681in" />

> multilevel analysis aids such as multilevel simulation.

<img src="&#39;./images/&#39;/media/image23.jpeg"
style="width:8.27778in;height:0.33681in" />

> l Development of special purpose hardware for CAD tasks.

<img src="&#39;./images/&#39;/media/image24.jpeg"
style="width:8.27778in;height:0.33681in" />

These research thrusts are being applied across the hierarchy

<img src="&#39;./images/&#39;/media/image25.jpeg"
style="width:8.27778in;height:0.33681in" />

of VLSI design. We view the design hierarchy to be composed of eight
levels:

<img src="&#39;./images/&#39;/media/image26.jpeg"
style="width:8.27778in;height:0.33681in" />

1.  Task level

2.  Architecture-definitionlevel

3.  Behavioral level

4.  Functional-structurelevel

5.  Logic-structure level

6.  Transistor or switch level

7.  Mask layout level

8.  Process level

<img src="&#39;./images/&#39;/media/image27.png"
style="width:8.27778in;height:1.00972in" />

> These levels are described in detail in (11. Design can be viewed as
> involving synthesis, verification and simulation. Ongoing CAD research
> projects in these three areas are described.

<img src="&#39;./images/&#39;/media/image28.png"
style="width:8.27778in;height:1.00972in" />

> 2.1. SYNTHESIS
>
> A synthesis tool takes a description of a desired system at one level
> in the design hierarchy and generates a

<img src="&#39;./images/&#39;/media/image29.jpeg"
style="width:8.27778in;height:0.33681in" />

> description at the next lower level in the hierarchy. A number of
> synthesis tools have been developed or are under development now.

<img src="&#39;./images/&#39;/media/image30.png"
style="width:8.27778in;height:0.67361in" />

> 2.1.1. System Synthesis

<img src="&#39;./images/&#39;/media/image31.jpeg"
style="width:8.27778in;height:0.33681in" />

> Design Representation and the System

<img src="&#39;./images/&#39;/media/image32.jpeg"
style="width:8.27778in;height:0.33681in" />

> Architect’s Workbench
>
> R.A. Walker, D.E. Thomas

<img src="&#39;./images/&#39;/media/image33.jpeg"
style="width:8.27778in;height:0.33681in" />

> The objective of this research is to develop a model of design
> representation, and then use that model to provide a designer’s
> workbench that will allow manipulation of designs

<img src="&#39;./images/&#39;/media/image34.jpeg"
style="width:8.27778in;height:0.33681in" />

> at high levels of abstraction. The model of design

<img src="&#39;./images/&#39;/media/image35.jpeg"
style="width:8.27778in;height:0.33681in" />

> representation being developed is characterized by three separate but
> coordinated domains of description - the behavioral domain, the
> structural domain, and the physical domain - each characterized by a
> particular design decision. Using the SCS language, developed at CMU,
> we can coordinate these domains to represent the entire design. We are
> also developing a system architect’s workbench that uses this model of
> design representation, and that will allow a designer to transform and
> analyze the design, particularly in the behavioral and structural
> domains. This workbench will extend our current system to higher
> levels of abstraction,

<img src="&#39;./images/&#39;/media/image36.png"
style="width:8.27778in;height:1.34653in" />

> and will include such transformations as structural

<img src="&#39;./images/&#39;/media/image37.jpeg"
style="width:8.27778in;height:0.33681in" />

> partitioning, process creation, and support for instruction-level
> pipelining.

<img src="&#39;./images/&#39;/media/image38.jpeg"
style="width:8.27778in;height:0.33681in" />

879

<img src="&#39;./images/&#39;/media/image40.jpeg"
style="width:8.27778in;height:0.12778in" />

<img src="&#39;./images/&#39;/media/image41.jpeg"
style="width:8.22222in;height:0.34028in" />

Interface Synthesis

<img src="&#39;./images/&#39;/media/image42.jpeg"
style="width:8.22222in;height:0.34028in" />

> J.A. Nestor, D.E. Thomas

This research investigates,the description and synthesis of digital
systems with complicated interface requirements. Previous work in high
level synthesis has successfully developed tools that can automatically
generate designs from

<img src="&#39;./images/&#39;/media/image43.png"
style="width:8.22222in;height:0.67986in" />

an abstract specification. However, these tools have

neglected the issues involved in designing interfaces. A

<img src="&#39;./images/&#39;/media/image44.jpeg"
style="width:8.22222in;height:0.34028in" />

method of describing systems with interfaces has been

developed. A new system of tools building on previous research uses
these extended descriptions to automatically

<img src="&#39;./images/&#39;/media/image45.jpeg"
style="width:8.22222in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image46.png"
style="width:8.22222in;height:1.02014in" />

for Multiple Processor Systems

<img src="&#39;./images/&#39;/media/image47.jpeg"
style="width:8.22222in;height:0.34028in" />

R.P. Bianchini Jr:, J.P. Shen

Recent research on parallel systems has clearly shown that the most
difficult problem faced by the system designer

<img src="&#39;./images/&#39;/media/image48.jpeg"
style="width:8.22222in;height:0.34028in" />

is interprocessor connection and communication. A methodology for the
automated design and implementation of interprocessor communication for
special-purpose multiple processor systems has been developed. It is
shown that for

<img src="&#39;./images/&#39;/media/image49.png"
style="width:8.22222in;height:0.67986in" />

> many special-purpose and mission-oriented systems the

interprocessor communication is deterministic and can be

<img src="&#39;./images/&#39;/media/image50.jpeg"
style="width:8.22222in;height:0.34028in" />

> specified at system inception. This specification, identified as the
> target architecture, can then be automatically mapped

<img src="&#39;./images/&#39;/media/image51.jpeg"
style="width:8.22222in;height:0.34028in" />

> or compiled onto a physical multiple processor system, identified as
> the host architecture, using a network traffic

<img src="&#39;./images/&#39;/media/image52.jpeg"
style="width:8.22222in;height:0.34028in" />

> scheduler. Algorithms for such a scheduler have been
>
> implemented. It is shown that the order of complexity of network
> scheduler components is polynomial rather than exponential as in
> classical solutions.

<img src="&#39;./images/&#39;/media/image53.png"
style="width:8.22222in;height:0.67986in" />

> Towards Knowledge-Based Synthesis
>
> of Analog Circuits

<img src="&#39;./images/&#39;/media/image54.jpeg"
style="width:8.22222in;height:0.34028in" />

> R. Harjani, R.A. Rutenbar

<img src="&#39;./images/&#39;/media/image55.jpeg"
style="width:8.22222in;height:0.34028in" />

> Although analog circuits do not exhibit the same rigid hierarchical
> structure as digital circuits, hierarchy maybe
>
> exploited by analog designers. Design still proceeds at

<img src="&#39;./images/&#39;/media/image56.jpeg"
style="width:8.22222in;height:0.34028in" />

> different levels of abstraction, but the coupling between
>
> levels and between objects within a level is much stronger,

<img src="&#39;./images/&#39;/media/image57.jpeg"
style="width:8.22222in;height:0.34028in" />

> and the interactions that must be planned for and designed
>
> (i.e., not logic values, but electrical, parasitic, electromagnetic
> and thermal considerations) are richer and more varied. Analog
> designers rely strongly on experience

<img src="&#39;./images/&#39;/media/image58.jpeg"
style="width:8.22222in;height:0.34028in" />

> with partial circuit topologies that meet classes of

<img src="&#39;./images/&#39;/media/image59.jpeg"
style="width:8.22222in;height:0.34028in" />

> constraints, and knowledge-intensive strategies for choosing
>
> the parameters that define each module or primitive device.

<img src="&#39;./images/&#39;/media/image60.jpeg"
style="width:8.22222in;height:0.34028in" />

> We are investigating design representations for a knowledge-
>
> based analog synthesis tool in the restricted domain of

<img src="&#39;./images/&#39;/media/image61.jpeg"
style="width:8.22222in;height:0.34028in" />

> CMOS analog-t-digital converters. The goal is to develop a
> representation that will not limit design to a set of fixed modules,
> but will helpdesign fully custom analog circuits.

<img src="&#39;./images/&#39;/media/image62.jpeg"
style="width:8.22222in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

> Synthesis by Delayed Binding of Decisions
>
> J. Rajan, D.E. Thomas
>
> A program called SUGAR is currently being developed
>
> to investigate the automatic synthesis of single chip
>
> microprogammed microprocessors from behavioral descriptions. Subtasks
> in complex problem solving activities
>
> like synthesis often in6eract. As a result, decisions .made
> prematurely can lead to poor designs. A least-commitment style of
> binding decisions has been developed that allows better design choices
> to be made by postponing important decisions until adequate
> information is available to make them. This design style partitions
> the design task into a
>
> sequence of temporally ordered- subtasks that cooperate during design.
> The sub#tasks consist of flow analysis, control
>
> flow transformations, control flow partitioning, data path
>
> model selection, and hardware allocation. Most subtasks
>
> have been implemented and the project is nearing completion.
>
> A Knowledge Source Based Synthesis System :
>
> A Feasibility Study
>
> D.L. Springer, D.E. Thomas
>
> This project investigates the organization of programs
>
> to automatically synthesize VLSI systems from the behavioral level to
> the register-transfer level. In particular we are exploring knowledge
> source based systems and an organization structuring language.
> Knowledge source based systems are composed of a set of independent
> knowledge sources which communi-cate via a software blackboard.
> Present knowledge source based systems include Hearsay-II
>
> which is a speech recognition program and ULYSSES (discussed below)
> which is a design environment for the
>
> logical and physical design of VLSI systems. Present synthesis systems
> for the upper levels of the design hierarchy
>
> do not allow the flexibility to: change knowledge, integrate
>
> different implementation styles, or deal with conflicting data, which
> a knowledge source based system would provide.
>
> This flexibility is highly desirable since this domain of the
> synthesis task is still largely in the research stage.
>
> Instruction Processor Pipeline, Design and Analysis
>
> R.J. Cloutier, D.E. Thomas
>
> The design of the stages and the control structures of a pipeline, for
> an instruction processor, are weakly supported
>
> by existing tools. The manual methods used today are similar to those
> that were originally used to describe the IBM 360/91. This lack of
> tools is hindering the development of advanced pipelined processors.
> The major problem is the diversity of control structures and the
> inability to deal with
>
> them in computer aided tools. Take for example, the partitioning of a
> processor into stages. Stage boundaries are proposed by considering
> timing relations and resource
>
> conflicts. A simulator is then written for that particular
>
> partitioning and the proposed control structure. Potential instruction
> streams are then run through the new pipeline

880

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

> modules, the system will be able to perform the layout of the

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

> refined. It is also believed that while human designers use
>
> metrics such as congestion estimates, number of wire
>
> crossings between partitions and balance of area between
>
> partitions, these metrics are only guidelines. Human
>
> designers also look for recognizable design situations such as
>
> busses, locations of pads on the periphery of the chip and
>
> familiar interconnections of components and handle these

situations in a manner that their experience has shown to be

<img src="&#39;./images/&#39;/media/image64.jpeg"
style="width:8.23611in;height:0.34028in" />

> most effective. A new approach will be investigated which

<img src="&#39;./images/&#39;/media/image65.jpeg"
style="width:8.23611in;height:0.34028in" />

combines a variety of metrics and viewpoints and will be

implemented with a multiple expert system.

<img src="&#39;./images/&#39;/media/image66.jpeg"
style="width:8.23611in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image67.png"
style="width:8.23611in;height:4.75972in" />

> cost. The goal of this research is to reduce the high cost of

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image68.png"
style="width:8.23611in;height:3.74028in" />

881

<img src="&#39;./images/&#39;/media/image69.jpeg"
style="width:8.23611in;height:0.34028in" />

> 2.2. VERIFICATION
>
> Linking Design Representations
>
> R.L. Blackburn, D.E. Thomas
>
> This research is concerned with the development of a means for linking
> design representations at different levels of
>
> abstraction. The linkage should provide the means of

identifying corresponding values and operators in two or more different
representations. Linkage will be accomplished by adding additional
information to design representations to describe how they relate to
each other. This work has applications in interactive debugging and
formal verification of synthesized data paths and controllers.

A Data-Structure Processor for VLSI

> Geometry Checking
>
> E.C. Carlson, R.A. Rutenbar
>
> A critical step in the verification of VLSI chip designs is the
> geometric analysis of IC masks. This geometric analysis performs the
> functions of design rule checking, connectivity
>
> analysis, transistor identification and parasitic extraction
>
> from the integrated circuit mask geometry. Scanline algorithms are at
> the base of many geometric analysis functions, and appear to be the
> best available solution both in speed and memory requirements to the
> needs of these verification tasks. Bigger machines to run these
> compute-
>
> intensive programs are an obvious solution, but are not
>
> necessarily the most cost effective. The design of special-purpose
> hardware is attractive since much of VLSI mask
>
> verification is based on similar scanline primitives. We have proposed
> an architecture that implements two fundamental scanline operations:
> boolean operations between mask layers, and region numbering within a
> mask layer. The proposed architecture is a pipeline that implements
> directly the basic operators needed to manipulate a scanline data
> structure. Using edges as its primitive operands, the architecture is
>
> capable of handling arbitrary <sub>polygon</sub> geometry. Preliminary
> simulations of the proposed hardware suggest
>
> that it is significantly faster than a VAX 11/780.
>
> A Localizing Circuit Extractor
>
> h4. Chew, A. J. Strojwas
>
> Process disturbances during the fabrication of a digital
>
> integrated circuit might affect the equivalent electrical
>
> circuit of the resulting chip. Unfortunately, the circuit extraction
> of the complete layout of a digital circuit layout is
>
> too computation-intensive a task to perform if one wants to
>
> see the effects of a given set of process disturbances. The goal of
> this project is to develop an extractor which, given the disturbance
> region and the type of the disturbance, will
>
> extract from the altered layout only the electrical components which
> might have undergone a change. The results of this tool will then be
> used to update a previously extracted circuit of the undisturbed
> layout.

2.3. SIMULATION

<img src="&#39;./images/&#39;/media/image70.png"
style="width:8.23611in;height:0.67986in" />

> Simulators developed at CMU span most of the levels in

the design hierarchy. One trend in the design of CMU’s simulators is the
use of abstractions for controlling detail. Abstraction can define a new
level which approximates the details of a lower level but with
simulation cost of a higher level. An example is VVASIM, a waveform
simulator that allows device and circuit properties at the cell level.

<img src="&#39;./images/&#39;/media/image71.png"
style="width:8.23611in;height:1.02014in" />

> Another trend is the use of hierarchy. Hierarchy can be used within a
> single design level by taking advantage of the natural hierarchy of
> the system under design. Hierarchy can also be used to mix two or more
> design levels. SAMSON, a mixed-level simulator, bridges the circuit
> and logic levels with more than two orders of magnitude performance
> increase over a traditional circuit simulator.

<img src="&#39;./images/&#39;/media/image72.png"
style="width:8.23611in;height:1.35972in" />

> A third trend is the increased use of statistical
>
> techniques. FABRICS uses statistics to model process

<img src="&#39;./images/&#39;/media/image73.jpeg"
style="width:8.23611in;height:0.34028in" />

> variations. The Hierarchical Statistical Simulator summarizes detailed
> behavior with a probability distribution function. A fourth trend is
> the use of symbolic and compile-

<img src="&#39;./images/&#39;/media/image74.jpeg"
style="width:8.23611in;height:0.34028in" />

> driven techniques. An example of this trend includes the switch level
> simulator COSMOS which is currently being developed at CMU. A number
> of simulation projects are described below in roughly the top-down
> order.

<img src="&#39;./images/&#39;/media/image75.png"
style="width:8.23611in;height:0.67986in" />

> 2.3.1. Functional Level Simulation

<img src="&#39;./images/&#39;/media/image76.jpeg"
style="width:8.23611in;height:0.34028in" />

> Functional Specification Simulation of Computers

<img src="&#39;./images/&#39;/media/image77.jpeg"
style="width:8.23611in;height:0.34028in" />

> S. Bose, D.P. Siewiorek
>
> This project is concerned with the functional description of
> computers. All constructs of a computer system can be

<img src="&#39;./images/&#39;/media/image78.jpeg"
style="width:8.23611in;height:0.34028in" />

> based on such functions, which can be written and incorporated into a
> general purpose language. Lisp has been

<img src="&#39;./images/&#39;/media/image79.jpeg"
style="width:8.23611in;height:0.34028in" />

> used for this purpose. A pseudo language called the Functional
> Specification Language (FSL) was designed to incorporate the features
> of functional languages as well as

<img src="&#39;./images/&#39;/media/image80.jpeg"
style="width:8.23611in;height:0.34028in" />

> special constructs for Hardware Description Languages

<img src="&#39;./images/&#39;/media/image81.jpeg"
style="width:8.23611in;height:0.34028in" />

> (HDL). FSL is actually Lisp with an added set of functions. These
> functions are arranged in two layers. The upper layer functions build
> on the lower layer and capture the unique features of HDLs for
> describing target computer instruction sets. The development of a tool
> is the subject of the ongoing research.

<img src="&#39;./images/&#39;/media/image82.png"
style="width:8.23611in;height:1.02014in" />

> 2.3.2. Switch-Level Simulation

<img src="&#39;./images/&#39;/media/image83.jpeg"
style="width:8.23611in;height:0.34028in" />

> COSMOS: A New Switch-Level Simulator
>
> R.E. Bryant

<img src="&#39;./images/&#39;/media/image84.jpeg"
style="width:8.23611in;height:0.34028in" />

> The COSMOS (Compiled Simulator for MOS) project aims to produce a high
> quality switch-level simulator with at

<img src="&#39;./images/&#39;/media/image85.jpeg"
style="width:8.23611in;height:0.34028in" />

> least an order of magnitude better performance than
>
> MOSSIM Il. The program also includes additional

<img src="&#39;./images/&#39;/media/image86.jpeg"
style="width:8.23611in;height:0.34028in" />

> capabilities such as concurrent fault simulation. Furthermore, it can
> easily be adapted for execution on any special purpose simulation
> accelerator that supports Boolean

<img src="&#39;./images/&#39;/media/image87.jpeg"
style="width:8.23611in;height:0.34028in" />

882

<img src="&#39;./images/&#39;/media/image88.jpeg"
style="width:8.23611in;height:0.34028in" />

evaluation. Unlike programs that operate directly on the

> transistor level description during simulation, COSMOS transforms the
> transistor network into a Boolean descripiion
>
> during a preprocessing step. This Boolean description, produced by a
> symbolic analyzer, captures all =PeCts of
>
> switch-level networks including bidirectional transistors, stored
> charge, different signal strengths, and indeterminate logic values.
> Unlike previous symbolic analyzers for MOS circuits, the COSMOS
> preprocessor produces very concise formulas, generally linear in the
> circuit size.
>
> Gaussian Elimination of Boolean Equations for
>
> Symbolic Simulation of MOS Transistor Networks
>
> T.J. Sheffler, R.E. Bryant
>
> This project is responsible for solving the network equations
> symbolically to arrive at Boolean equations which
>
> represent the behaviour of the network. A method closely related to
> Gaussian elimination seems promising. Instead of solving the equations
> in the domain of real numbers, the elimination and backsolving steps
> will be performed in the domain of Booleans. Much has been written on
> the relation
>
> between Gaussian elimination and solving systems of Boolean equations,
> however, there has been no clear discussion of this topic with respect
> to switching circuits.
>
> The systems of equations to be solved in this application are sparse
> in nature, thus sparse matrix techniques will be explored.
>
> Manipulation and Reduction of Boolean Expressions
>
> Represented as Directed Acyclic Graphs
>
> KS. Brace, R.E. Bryant
>
> This project deals with the maintenance and
>
> simplification of structures which store representations of
>
> Boolean formulas. A formula is represented as a directed acyclic graph
> (dag). A dag resembles a parse tree except that a subgraph may be
> shared by more than one branch,
>
> yielding a more compact representation. When a new
>
> formula is defined simplifications must be made in a
>
> standardized way so that, equivalent formulas may be
>
> recognized as such. The shared subgraphs of the dag
>
> structure complicate this. The primary concern of this project deals
> with the trade-off between the computation involved in simplification
> and the time and space saved by having an optimally simplified dag.
>
> 2.3.3. Timinp/Circuit Simulation
>
> SPECS2 : A Timing Simulator
>
> C. Visweswariah, R.A. Rohrer
>
> This project is aimed at the development of a timing simulator called
> SPECSZ. The timing simulator is based on a tree/link analysis of the
> circuit. Table look up is used for model evaluation. An event-driven
> approach is employed for
>
> simulation. An event is the movement of a device from one
>
> region of its characteristics to the next. An event is processed,
> generating a new event for the time when the device is expected to
> move out of the present region of its

characteristics. This event is scheduled for the future. Time moves
ahead to the next scheduled event and the process

<img src="&#39;./images/&#39;/media/image89.png"
style="width:8.25in;height:0.67986in" />

continues. A new modeling approach based on the conservation of charge
and energy is used to build the table models. The simulator does not
rely on complex models for good numerical conditioning or to guarantee
reliability.

<img src="&#39;./images/&#39;/media/image90.png"
style="width:8.25in;height:0.67986in" />

Statistical Timing Analysis

> J. Benkoski, A. J. Strojwas

<img src="&#39;./images/&#39;/media/image91.jpeg"
style="width:8.25in;height:0.34028in" />

> The purpose of this project is to develop a tool that will provide the
> designer with a fast but accurate statistical estimate of the delays
> in VLSI circuits. At first the circuit is partitioned into logically
> meaningful blocks. Each block will then undergo several Elogic
> (Electrical Logical) simulations in order to fully characterize its
> delay as a function of the process parameters. The result of this
> analysis will be the input to output delays for this block and will be
> decomposed into three sub-delays: the input delay, the intrinsic
> delay, and the output delay. While the first is a function of the
> input slopes and the last depends on the loading conditions, the
> intrinsic delay is independent of the environment in which the block
> is placed. By using this technique, we can afford to analyze only
> unique blocks. The last part of our estimation process involves either
> an event driven simulation of the circuit at the block level or a
> longest path evaluation.

<img src="&#39;./images/&#39;/media/image92.png"
style="width:8.25in;height:2.72014in" />

> A Macromodelling Approach for VLSI Simulation
>
> S.R. Nassif, S.W. Director

<img src="&#39;./images/&#39;/media/image93.jpeg"
style="width:8.25in;height:0.34028in" />

> We have developed a methodology for the simulation of
>
> cell-based MOS designs. We attempt to exploit the regularity of such
> designs by building macromodels of the individual cells which are
> capable of predicting circuit-level electrical performance. In
> particular, we derive analytical approximations for waveforms that are
> generated by typical device-level output stage topologies, and fit
> these models to waveforms generated by circuit simulation. Macromodels
> are generated for these cells, such that the output of these

<img src="&#39;./images/&#39;/media/image94.png"
style="width:8.25in;height:1.35972in" />

> macromodels are waveforms, and the inputs are designable parameters
> such as layout, as well as circuit parameters such

<img src="&#39;./images/&#39;/media/image95.jpeg"
style="width:8.25in;height:0.34028in" />

> as fan-out. An event-driven, waveform-based simulator,
>
> called WASIM has been developed which employs these macromodelled
> cells. The basic events in this simulator are

<img src="&#39;./images/&#39;/media/image96.jpeg"
style="width:8.25in;height:0.34028in" />

> waveform transitions. WASIM is capable of achieving near
>
> logic-simulator speeds, while accurately predicting waveforms, delays,
> and hazards \[Z\].

<img src="&#39;./images/&#39;/media/image97.png"
style="width:8.25in;height:0.67986in" />

> Efficient Modeling of Small-Geometry MOSFETs
>
> M. J. Saccamango, A. J. Strojwas

<img src="&#39;./images/&#39;/media/image98.jpeg"
style="width:8.25in;height:0.34028in" />

> This project is concerned with developing more accurate models of
> small-geometry MOSFET’s for circuit simulation

<img src="&#39;./images/&#39;/media/image99.jpeg"
style="width:8.25in;height:0.34028in" />

> purposes. We are currently deriving methods for
>
> determining device parameters (threshold voltage, body

<img src="&#39;./images/&#39;/media/image100.jpeg"
style="width:8.25in;height:0.34028in" />

> factor and channel-length modulation parameter) with efficient
> physically-based models. These methods will be a part, of the device
> simulation portion of the seatistical process/device simulator FABRICS
> II. This phase of the project is focused on the special modeling
> problems of modern MOSFET devices, i.e. those with small-geometries,

<img src="&#39;./images/&#39;/media/image101.png"
style="width:8.25in;height:1.02014in" />

883

<img src="&#39;./images/&#39;/media/image102.jpeg"
style="width:8.25in;height:0.34028in" />

> nonuniformly-doped channels and/or lightly-doped source/drain regions.
> The next project phase will involve the use of the physically-based
> models to extend the FABRICS II

<img src="&#39;./images/&#39;/media/image103.png"
style="width:8.22222in;height:0.67986in" />

> device simulation to produce I-V characteristics. From these
> characteristics we hope to extract device models for circuit
> simulation which better reflect the bias dependencies of the device
> parameters. The availability of these I-V curves will also allow the
> extraction of device parameters to meet the modeling requirements of
> many circuit simulators presently in use.

<img src="&#39;./images/&#39;/media/image104.png"
style="width:8.22222in;height:1.02014in" />

> Tree/link Based Mixed-mode Circuit Simulator

<img src="&#39;./images/&#39;/media/image105.jpeg"
style="width:8.22222in;height:0.34028in" />

X. Huang, R.A. Rohrer

<img src="&#39;./images/&#39;/media/image106.jpeg"
style="width:8.22222in;height:0.34028in" />

This project aims at transcending the borders between switch level
simulation and circuit level simulation of VLSI. A mixed mode capability
will be accomplished by modeling the circuit devices on variable levels
of accuracy. Spatial and temporal latency can be exploited by replacing
dormant devices with the simplest models, which very often may be ideal
switches. To accommodate these different models,

<img src="&#39;./images/&#39;/media/image107.png"
style="width:8.22222in;height:1.02014in" />

> tree/link repartitioning will be employed to avoid ill-

conditioning and to effect fast convergence of iterative solution.

<img src="&#39;./images/&#39;/media/image108.jpeg"
style="width:8.22222in;height:0.34028in" />

> Table Look-Up Device Modeling for a Charge and
>
> Energy Conserving VLSI Circuit Timing Simulator

<img src="&#39;./images/&#39;/media/image109.jpeg"
style="width:8.22222in;height:0.34028in" />

> C. DellaTove, R.A. Rohrer

<img src="&#39;./images/&#39;/media/image110.jpeg"
style="width:8.22222in;height:0.34028in" />

> Conventional simulators violate basic laws of physics,
>
> such as the conservation of charge and energy. A new method of device
> modeling has been proposed that is aimed at charge and energy
> conservation in circuit simulation.

<img src="&#39;./images/&#39;/media/image111.jpeg"
style="width:8.22222in;height:0.34028in" />

> This project involves the development of this modeling effort so that
> it could be incorporated into a simulator, the premise being that this
> simulator would, therefore, be more reliable

<img src="&#39;./images/&#39;/media/image112.png"
style="width:8.22222in;height:0.67986in" />

> and efficient than existing simulators. This modeling effort will
> incorporate table look-up methods of device modeling consistent with
> the above constraints. Thus, values entered into these tables will be
> derived in a manner that ensures that charge and energy are conserved.
> These tables will be built in the most memory-efficient manner
> possible.

<img src="&#39;./images/&#39;/media/image113.png"
style="width:8.22222in;height:1.02014in" />

> 2.3.4. Yield Prediction and Maximization

<img src="&#39;./images/&#39;/media/image114.jpeg"
style="width:8.22222in;height:0.34028in" />

Yield Simulation for Integrated Circuits

> H. Walker, S.W. Director

<img src="&#39;./images/&#39;/media/image115.jpeg"
style="width:8.22222in;height:0.34028in" />

> We have developed a catastrophic fault yield simulator VLASIC (VLSI
> LAyout Simulation for Integrated Circuits). VLASIC is a Monte Carlo
> simulator that uses defect models and statistics to place random
> catastrophic point defects on a chip layout and determine what circuit
> faults, if any, have occurred. The defect models are described in
> tables, and so are readily extended to new processes or defect types.
> The defect statistical model is based on actual fabrication line

<img src="&#39;./images/&#39;/media/image116.png"
style="width:8.22222in;height:1.02014in" />

> data, and has not appeared before in the literature. The output of
> VLASIC is a population of chip samples with the

<img src="&#39;./images/&#39;/media/image117.jpeg"
style="width:8.22222in;height:0.34028in" />

> same distribution of circuit faults as observed in the fabrication
> line. This circuit fault information can be used to predict yield,
> optimize design rules, generate test vectors, evaluate redundancy,
> etc. We have also developed a simple redundancy analysis system as an
> example application.

<img src="&#39;./images/&#39;/media/image118.png"
style="width:8.22222in;height:0.67986in" />

> A Realistic Yield Simulator for IC Failures
>
> I. Chen, A. J. Strojwas
>
> This research is aimed at developing a CAD tool to realistically
> estimate the yield losses due to IC structural
>
> failures, This tool extends the statistical design rule
>
> developer to an accurate and efficient yield simulator. The
> methodologv adopted by the simulator accounts for most of

the mechanisms which cause IC yield degradation due to structural
failures. For computational efficiency, analytical method rather than
Monte Carlo method is used. There are

> two main parts in this simulator: formulation of yield

statistics in hierarchical levels and derivation of the

Probability Of Failure (POF) for layout patterns. In the first part, we
have successfully derived yield statistics which

> consider the effects elf defect size sensitivity, globally

nonuniform distribution (wafer level), and local clustering effects. In
the second part, a theoretical method to find the POF for most of the
simple patterns has been developed. Thus, given a set of layout design
rules, this simulator will be able to predict yield in a hierarchical
manner on the device level, chip level, or even wafer level.

> Statistical Integrated Circuit Design:
>
> Parametric Yield Maximization

1.  Low, S.W. Director

> The goal of this project is to develop an efficient way to
>
> optimize the production yield of VLSI circuits using
>
> statistical circuit design techniques. Specifically, we will
>
> address the parametric yield maximization problem using fabrication
> process control parameters (such as implantation dose and energy) and
> device geometries as designable
>
> parameters. Our approach differs from most previous work in this area
> in that we have chosen the space of process inputs instead of device
> parameters as part of our design space. This distinction is
> particularly relevant in integrated
>
> circuits since the device parameters are correlated. Moreover,
> previous methods require separate optimizations to be performed at the
> process and circuit levels which may result in suboptimal solutions.
> Two major obstacles can be identified in our effort. Firstly, accurate
> yield estimation is
>
> very computationally expensive due to the cost of
>
> simulations. Therefore, techniques must be found to reduce
>
> the cost without compromising accuracy. Secondly, the
>
> dimensionality of the problem must be brought down to a
>
> manageable level. This may be achieved by exploiting
>
> certain properties of integrated circuit design such as regularity and
> hierarchy.

3\. MANUFACTURING

> Minimizing cost-per-chip is the main objective in VLSI design,
> manufacturing and testing. Our research program in
>
> the area of manufacturing has this goal as its principal objective. We
> have recognized the fact that in VLSI circuit design, statistical
> characterization of the fabrication process is a necessity in order to
> describe the random fluctuations in processing conditions, material
> parameters and point defects
>
> that cause drops in production yield. This process level

884

<img src="&#39;./images/&#39;/media/image119.jpeg"
style="width:8.22222in;height:0.34028in" />

information can be abstracted into the higher levels, i.e.

circuit, logic or functional levels, where it can be used to produce
realistic IC designs or test programs.

> Towards this end the statistical process/device

simulator FABRICS II was developed to provide a common

denominator for the integrated CAD/CAM \[3\] system with

the capabilities shown in Figure 3. FABRICS II employs

efficient (numerical or analytical) models of the fabrication

steps and semiconductor devices manufactured in a number

of technologies (NMOS, CMOS and bipolar). FABRICS

simulation system accepts IC layout and process description,

> and generates model parameters for the active devices and
>
> par&tics. These parameters are compatible with the models
>
> implemented in such a popular circuit simulator, as SPICE.

The CPU time consumed ‘by FABRICS for the process/device

simulation is usually a small fraction of the time consumed

> in the circuit simulation stage. The accuracy of simulation
>
> is accomplished by tuning FABRICS to a particular
>
> fabrication process by a statistical optimization system
>
> called PROMETHEUS 131. As a result of tuning, device
>
> parameters obtained from FABRICS are in good agreement
>
> with the parameters measured in the real fab lines. The
>
> current status of software in the CAM system is shown in Figure 4.
>
> l Nominal design in terms of process parameters

<img src="&#39;./images/&#39;/media/image120.png"
style="width:8.23611in;height:0.67986in" />

> (e.g. minimization of power-delay product of a
>
> dynamic RAM in terms of gate oxidation parameters).

<img src="&#39;./images/&#39;/media/image121.jpeg"
style="width:8.23611in;height:0.34028in" />

> l Worst-case design in terms of statistically
>
> independent process disturbances.

<img src="&#39;./images/&#39;/media/image122.jpeg"
style="width:8.23611in;height:0.34028in" />

> . Parametric yield maximization in the space of layout and process
> parameters.

<img src="&#39;./images/&#39;/media/image123.jpeg"
style="width:8.23611in;height:0.34028in" />

> A complete integrated system for process diagnosis
>
> PROD 14) has been developed and it uses FABRICS for

<img src="&#39;./images/&#39;/media/image124.jpeg"
style="width:8.23611in;height:0.34028in" />

> efficient fault simulation. PROD identifies faults in the
>
> process that caused a drop in yield for a particular

<img src="&#39;./images/&#39;/media/image125.jpeg"
style="width:8.23611in;height:0.34028in" />

> production run. The approach used in PROD is based on the
>
> analysis of distributions of IC performances and employs
>
> statistical pattern recognition techniques.

<img src="&#39;./images/&#39;/media/image126.png"
style="width:8.23611in;height:0.67986in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image127.png"
style="width:8.23611in;height:1.02014in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image128.png"
style="width:8.23611in;height:1.7in" />

> Figure 3. CAD/CAM System Capabilities
>
> To facilitate synthesis of new fabrication processes, an
>
> interactive process interpreter/compiler PI/C \[3\] has been
>
> recently added to the simulation system. <sup>It</sup>
> <sup>employs</sup> <sup>a</sup>
>
> graphical process editor PED \[3\] and allows the user to
>
> specify the process by defining the lithographic masks and
>
> process conditions. The user can perform incremental
>
> simulations and view the simulation results which are
>
> displayed in the form of impurity profiles and device cross-
>
> sections. Extensive error checking is performed by the system to help
> in the synthesis.
>
> FABRICS II combined with a circuit simulator (SPICE
>
> or SAMSON) can be employed for a number of tasks ranging
>
> from the design verification/optimization to process
>
> diagnosis, to statistical process control. The design
>
> optimization tasks include:
>
> Figure 4. CAD/CAM Software.

<img src="&#39;./images/&#39;/media/image129.jpeg"
style="width:8.23611in;height:0.34028in" />

> To obtain realistic estimates of final production yield,

the probability distribution of spot defects (e.g. shorts or

<img src="&#39;./images/&#39;/media/image130.jpeg"
style="width:8.23611in;height:0.34028in" />

breaks due to local lithographic errors) has to be taken into

account together with the parametric variations. A yield

<img src="&#39;./images/&#39;/media/image131.jpeg"
style="width:8.23611in;height:0.34028in" />

simulator, called VLASIC, has been developed and can be

used for prediction of the decrease in yield due to spot

> defects. For circuit design purposes, all the random factors

<img src="&#39;./images/&#39;/media/image132.jpeg"
style="width:8.23611in;height:0.34028in" />

> affecting IC layout have to be translated into layout design

rules. A statistical design rule developer STRUDEL (51 has

<img src="&#39;./images/&#39;/media/image133.jpeg"
style="width:8.23611in;height:0.34028in" />

> been implemented to derive rules which maximize total yield.

Two ongoing projects in this area are described below.

<img src="&#39;./images/&#39;/media/image134.jpeg"
style="width:8.23611in;height:0.34028in" />

> Statistical Quality Control for VLSI

<img src="&#39;./images/&#39;/media/image135.jpeg"
style="width:8.23611in;height:0.34028in" />

> Fabrication Processes
>
> P.K. Mozumder, A.J. Strojwas

<img src="&#39;./images/&#39;/media/image136.jpeg"
style="width:8.23611in;height:0.34028in" />

> Random fluctuations, which are inherent in any IC
>
> fabrication process, cause the production yield to drop

<img src="&#39;./images/&#39;/media/image137.jpeg"
style="width:8.23611in;height:0.34028in" />

> significantly below 100%. The faults which cause the yield
>
> drop can be classified as catastrophic and parametric. This

<img src="&#39;./images/&#39;/media/image138.jpeg"
style="width:8.23611in;height:0.34028in" />

> project deals with monitoring and controlling the IC

<img src="&#39;./images/&#39;/media/image139.jpeg"
style="width:8.23611in;height:0.34028in" />

a85

<img src="&#39;./images/&#39;/media/image140.jpeg"
style="width:8.22222in;height:0.34028in" />

fabrication process via statistical quality control. A cost optimization
approach to the statistical quality control of IC fabrication processes
has been taken. The project aims at creating a system which will, after
every step in the fabrication sequence, make decisions as to whether the
lot as a whole or in part is to be rejected from further processing. The
system, given the constraints, is expected to develop selection criteria
for the in-line measurements, which are then used by the system to make
quality control decisions.

<img src="&#39;./images/&#39;/media/image141.png"
style="width:8.22222in;height:1.35972in" />

The concept of process observability via in-line

measurements, appropriate models necessary for process control, and
algorithms for quality control based on yield maximization objectives
have been developed.

<img src="&#39;./images/&#39;/media/image142.png"
style="width:8.22222in;height:0.67986in" />

Adaptive Control of the IC Fabrication Process

<img src="&#39;./images/&#39;/media/image143.jpeg"
style="width:8.22222in;height:0.34028in" />

C.R. Shyamsundar, A. J. Strojwas

This research deals with adaptive control of VLSI fabrication processes.
Based on the in-line measurements that

<img src="&#39;./images/&#39;/media/image144.jpeg"
style="width:8.22222in;height:0.34028in" />

are made during the fabrication of integrated circuits, decisions will
be made regarding the values of the future process parameters. Models
relating the process parameters to in-lines and circuit performances,
will be used for this purpose. These models were built using MULREG
(MUlti-Layer REGression program), which has been specially

<img src="&#39;./images/&#39;/media/image145.png"
style="width:8.22222in;height:1.02014in" />

developed for this purpose. An acceptability region in the space of
process parameters is also used to arrive at the decisions. The aim will
be to maximize the total profit from

<img src="&#39;./images/&#39;/media/image146.jpeg"
style="width:8.22222in;height:0.34028in" />

> the fabrication line. With this in mind, a minimum acceptable yield
> will be determined at each stage. This will not be a constant but will
> depend on a number of factors including the current stage in the
> fabrication process. If at a particular stage in the IC fabrication
> process, the predicted yield is greater than this acceptable yield
> then the process parameters for the future stages will not be
> modified, otherwise one or more of these process parameters will be
> modified so as to meet the yield criterion.

<img src="&#39;./images/&#39;/media/image147.png"
style="width:8.22222in;height:1.7in" />

1.  TESTING

<img src="&#39;./images/&#39;/media/image148.jpeg"
style="width:8.22222in;height:0.34028in" />

> We have started a research effort to develop a new methodology and
> associated software tools for the testing of MOS VLSI circuits. Most
> of the existing fault modeling and test generation techniques are
> based on the traditional scenario of putting many TTL SSI/MSI packages
> on a

<img src="&#39;./images/&#39;/media/image149.png"
style="width:8.22222in;height:0.67986in" />

> printed circuit board. It is believed that the efficient and

<img src="&#39;./images/&#39;/media/image150.jpeg"
style="width:8.22222in;height:0.34028in" />

> effective testing of MOS VLSI circuits requires the development of new
> approaches and tools. We believe the following three problems
> associated with traditional testing must be addressed.

<img src="&#39;./images/&#39;/media/image151.png"
style="width:8.22222in;height:0.67986in" />

> 1\. Technology independent fault model.
>
> Regardless of the implementation technology, the single line stuck at
> fault model is the most widely

<img src="&#39;./images/&#39;/media/image152.jpeg"
style="width:8.22222in;height:0.34028in" />

> used fault model. We believe that, for VLSI testing, the fault model
> should be based on the physical defects and should take into account
> the technology, layout, and process characteristics.

<img src="&#39;./images/&#39;/media/image153.png"
style="width:8.22222in;height:1.68472in" />

> 2\. Unranked fault list. Traditionally, the relative importance of
> different faults is not
>
> considered. We believe that not all faults are
>
> equally likely or equally important. It may be more cost effective to
> rank the fault list and appropriately order the test set so as to
> detect the most likely to occur faults first.
>
> 3\. Single level approach. Most existing testing methodologies and
> tools assume the logic gate level model. Although MS1 level macros are
> often used in logic simulators, most systematic test
>
> generation algorithms require the gate level
>
> representation. We believe, just as in design, a
>
> new testing methodology should involve a multiple level or
> hierarchical approach in order to ease the complexity burden.
>
> As part of our initial step towards the integration of

CAD/CAM/CAT, the concept of a manufacturing-based methodology for
fabrication testing is being developed. This methodology addresses the
above three problems in the following two ways:

> . A customized fault list is generated for each circuit being tested.
> Faults in the list take into account the technology, layout, and
> fabrication characteristics, and can be grouped into different
>
> types depending on the faulty behaviors. Each fault list can be ranked
> according to relative likelihood of occurrence of the faults.
>
> l Starting with likely defects at the physical level, faults are
> extracted to the transistor, logic or even functional levels. Test
> pattern generation is performed separately for different fault types,
> at
>
> possibly different levels. Test pattern
>
> composition is then performed to produce the final test set.
>
> The proposed manufacturing-based testing scenario is illustrated in
> Figure 5. Two ongoing projects in this area arc presented below.
>
> Inductive Fault Analysis
>
> F.J. Ferguson, J.P. Shen
>
> Our first project in this area addresses the problem of
>
> the inappropriateness of the traditional fault model. Our underlying
> assumption is that circuit level faults are caused by physical defects
> which are inherent in the IC fabrication process. A technique called
> Inductive Fault Analysis (IFA) has been developed which allows the
> transistor or logic level faulty behaviors of a given MOS integrated
> circuit to be
>
> extracted from the layout level using process level information
> concerning spot defects IS\].
>
> IFA is an example of crossing multiple levels of the design hierarchy
> and involving elements of CAD, CAM and
>
> CAT. It is a systematic fault extraction procedure that
>
> spans the process, layout, transistor, and logic levels. A higher
> level fault model is developed based on conclusions
>
> <img src="&#39;./images/&#39;/media/image154.jpeg"
> style="width:8.22222in;height:0.19792in" />

<img src="&#39;./images/&#39;/media/image156.jpeg"
style="width:8.22222in;height:0.34028in" />

> Layout

<img src="&#39;./images/&#39;/media/image157.jpeg"
style="width:8.22222in;height:0.34028in" />

> Defect

<img src="&#39;./images/&#39;/media/image158.jpeg"
style="width:8.22222in;height:0.34028in" />

> Statistic
>
> \_\_\_\_\_\_\_\_\_-
>
> Rded;

<img src="&#39;./images/&#39;/media/image159.jpeg"
style="width:8.22222in;height:0.34028in" />

> Fault List :

<img src="&#39;./images/&#39;/media/image160.jpeg"
style="width:8.22222in;height:0.34028in" />

> 0Circuit

<img src="&#39;./images/&#39;/media/image161.jpeg"
style="width:8.22222in;height:0.34028in" />

> ATE

<img src="&#39;./images/&#39;/media/image162.png"
style="width:8.22222in;height:2.37986in" />

> Figure 5. Manufacturing-Based Testing Scenario.

<img src="&#39;./images/&#39;/media/image163.jpeg"
style="width:8.22222in;height:0.34028in" />

drawn from examining particular defects at the lower level, hence the
word “inductive”.

<img src="&#39;./images/&#39;/media/image164.jpeg"
style="width:8.22222in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image165.png"
style="width:8.22222in;height:2.37986in" />

> Initial application of the IFA procedure to an example
>
> circuit led to a number of very interesting observations \[6\].

<img src="&#39;./images/&#39;/media/image166.jpeg"
style="width:8.22222in;height:0.34028in" />

> Only 64% of the extracted faults can be modeled by the
>
> traditional single and multiple line stuck-at fault model. Not all
> faults are equally likely, and unusual faults, such a.~

<img src="&#39;./images/&#39;/media/image167.jpeg"
style="width:8.22222in;height:0.34028in" />

> the creation of new transistors, are possible. Only 3% of the
>
> faults involve transistors stuck at open, whereas 30% of the

<img src="&#39;./images/&#39;/media/image168.jpeg"
style="width:8.22222in;height:0.34028in" />

> faults are bridging faults. The IFA procedure can be used to
>
> \(1\) characterize potential faults in a circuit; (2) evaluate the

<img src="&#39;./images/&#39;/media/image169.jpeg"
style="width:8.22222in;height:0.34028in" />

> true effectiveness of traditional test sets; (3) provide a basis

<img src="&#39;./images/&#39;/media/image170.jpeg"
style="width:8.22222in;height:0.34028in" />

> Figure 6. Inductive Fault Analysis
>
> Implementation Environment.

for more effective test generation; and (4) uncover likely

faults that are very difficult to test.

Switch-Level Test Generation

S.H. Robinson, J.P. Shen

> This project focuses on automatic generation of test

patterns to screen out defective CMOS integrated circuits

during fabrication testing. The algorithm developed uses a

switch-level model in a search, similar to the D-Algorithm, to

find tests for a specified fault list. Backtracking is allowed

> at each step in the search where multiple alternatives exist,

so that if a test exists, it will be found by the algorithm. At

the switch-level, transistors are viewed as bilateral switches,

> and a composite-valued algebra is used to represent the node

values within the good and faulty circuits. The switch-level

> representation of CMOS circuits provides enough detail to
>
> model the faults and the bidirectional nature of CMOS
>
> circuits while retaining enough abstraction to be
>
> computationally efficient \[7\].
>
> We have implemented this test generation methodology
>
> and embedded it within a test generation and test evaluation
>
> environment. Using this system, switch-level test generation
>
> and fault simulation for several small example circutis has
>
> been performed. The fault coverage results are encouraging
>
> and suggest that test generation is feasible at the switch level and
> is a promising area of research.

887

> 5\. DESIGN ENVIRONMENT

In order to achieve an interactive design automation system that is made
up of a set of disparate tools, we must, develop a computing environment
that has

> l the ability to allow various programs that have
>
> incompatible input and output languages to communicate with each
> other;
>
> l the ability to manipulate a variety of hardware description
> languages and to be able to resolve
>
> incompatibilities that may result;
>
> l the ability to organize the flow of information between programs to
> realize a specified design task;
>
> l the ability to implement automatically a diverse set, of design
> tasks andmethodologies;
>
> . the ability to allow the designer to arbitrarily
>
> interrupt a design task (such as a specified program execution
> sequence) and restart or redirect the sequence of operations;
>
> . the ability to explain its sequence of design activities to the
> designer, and to explain the reasons for particular design decisions;
>
> l the capability of easily introducing new computer
>
> .aids or tools or substituting newer tools for older ones; and
>
> l the ability to keep track of all design attempts for a .particular
> VLSI chip, and to make some
>
> comparison of these attempts, based on quantitative measures.
>
> 5.1. EXPEELT-SYSTEM BASED ENVIRONMENT
>
> We refer to a computing environment which has the
>
> above capablities as a VLSI design environment. Such an enviroument,
> called ULYSSES IS\], has been developed and
>
> employs AI concepts to achieve the flexibility which the above
> attributes require.
>
> ULYSSES -- An Expert-System Based VLSI
>
> Design Environment
>
> ML\. Bushnell, S.W. Director
>
> The ULYSSES project has created a design environment appropriate for
> VLSI design. Conceptually, the environment may be viewed as a
> knowledge-based expert system for
>
> choosing which CAD program to execute next,. The emphasis here is on
> controlling existing CAD tools, rather than on writing new ones.
> Furthermore, the environment is designed so that it will be very easy
> to substitute new, and
>
> hopefully better, CAD tools for existing tools. The environment
> employs a blackboard architecture originally employed in the
> Hearsay-II speech understanding system. This architecture is
> particularly suited for the VLSI problem domain, where many
> independent CAD tools must be
>
> controlled in order to solve various design problems. The
>
> &a&board is a global data base used for communicating information
> .among various VLSI CAD tools, which are called knowledge sources. A
> language was designed to conveniently describe VLSI design activities,
> which are called scripts. An
>
> archival file backup system and a design space are part of ULYSSES.
> The design space supports comparisons among competing design points,
> and both the environment, and the designer can switch design
> activities to a different design point when the current one no longer
> appears viable.

<img src="&#39;./images/&#39;/media/image171.png"
style="width:8.25in;height:1.02014in" />

.Knowledge-Based Chi:p Planning

<img src="&#39;./images/&#39;/media/image172.jpeg"
style="width:8.25in;height:0.34028in" />

> A.M. Dewey, S.W. Director

<img src="&#39;./images/&#39;/media/image173.jpeg"
style="width:8.25in;height:0.34028in" />

> The objective of this research is to develop computer-aided support
> for the tzsk of chip planning by utilizing the
>
> capabilities of the UL,YSSES environment. The chip planning task will
> assist in the incremental development of

<img src="&#39;./images/&#39;/media/image174.jpeg"
style="width:8.25in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image175.png"
style="width:8.25in;height:0.67986in" />

> and determining realistic performance goals. The purpose of the chip
> planning activities is to produce a credible chip-level specification
> that can be used to more efficiently conduct the

<img src="&#39;./images/&#39;/media/image176.jpeg"
style="width:8.25in;height:0.34028in" />

> subsequent detailed IC design and implementation phases. Emphasizi.ng
> chip plann.ing is in contrast to current design practices where the
> chip-level specification either simply does not exist or is an
> informal description which serves only as a

<img src="&#39;./images/&#39;/media/image177.png"
style="width:8.25in;height:0.67986in" />

> guideline for the implementers. Using the chip-level specification as
> a more formal part, of the integrated circuit
>
> design process can lead to a more efficient design methodology because
> major design errors at, the specification level are, in general,
> easier to detect and correct. Thus, chip planning can help to avoid
> costly redesigns when, halfway into an expensive design cycle, it is
> discovered that the

<img src="&#39;./images/&#39;/media/image178.png"
style="width:8.25in;height:1.02014in" />

> initial specifications were incorrect, incomplete, or unrealistic.

<img src="&#39;./images/&#39;/media/image179.jpeg"
style="width:8.25in;height:0.34028in" />

> 5.2. USER INTERFACE

<img src="&#39;./images/&#39;/media/image180.jpeg"
style="width:8.25in;height:0.34028in" />

> With the advent of a design environment such as ULYSSES, we may view
> the role of the IC designer as that
>
> of an intelligent advisor communicating with an

<img src="&#39;./images/&#39;/media/image181.jpeg"
style="width:8.25in;height:0.34028in" />

> “intelligent” design environment. In such a situation, it

.\* would become very difficult for the designer to express his
intentions in a traditional manner. In order to allow the designer the
greatest degree of flexibility in using the design automation system, we
feel that a natural language interface is required.

<img src="&#39;./images/&#39;/media/image182.png"
style="width:8.25in;height:1.02014in" />

> The task of building a natural language interface for
>
> CAD is not, unfortunately, simply ‘one of applying an existing AI
> technology to a new domain. Though the study of previous natural
> language interfaces is a rich source of ideas, it also underlines the
> imperfections of these interfaces, and the need for a fresh approach.
> A key component of a natural language interface is the &gt;parser,
> which analyses a sentence or sentence fragment and produces some kind
> of structured representation for it,. Previous natural language
> interfaces, in general, have addressed this issue of parsing in rather
> piecemeal ways. Their coverage of constructions in English (the
> natural language most interfaces have dealt with) has been motivated
> and dictated by the domain of application of these interfaces, and not
> by any systematic study of the structure of English. For the goals of
> some of these interfaces, these limitations have not been detractions,
> but, they have restricted the utility of the interfaces to other
> domains. Since most natural language interfaces have been

<img src="&#39;./images/&#39;/media/image183.png"
style="width:8.25in;height:2.37986in" />

888

<img src="&#39;./images/&#39;/media/image184.jpeg"
style="width:8.25in;height:0.34028in" />

> <img src="&#39;./images/&#39;/media/image185.jpeg"
> style="width:8.25in;height:0.34028in" /> domains, or, by

self-admission, never intended for l’realll use, their

<img src="&#39;./images/&#39;/media/image186.jpeg"
style="width:8.25in;height:0.34028in" />

application to substantial problems has always been problematic.

<img src="&#39;./images/&#39;/media/image187.jpeg"
style="width:8.25in;height:0.34028in" />

In contrast to the domains for which most natural language interfaces
have been intended, the CAD domain is substantial and complex. Hence, we
have developed a new

<img src="&#39;./images/&#39;/media/image188.jpeg"
style="width:8.25in;height:0.34028in" />

> approach to natural language understanding. Based on this approach, we
> have implemented an initial version of a

<img src="&#39;./images/&#39;/media/image189.jpeg"
style="width:8.25in;height:0.34028in" />

> natural language interface called CLEOPATRA \[9\] that deals with
> circuit simulation post-processing.

<img src="&#39;./images/&#39;/media/image190.jpeg"
style="width:8.25in;height:0.34028in" />

> While CLEOPATRA is currently limited to the sub-
>
> domain of circuit simulation post-processing, future extensions will
> gradually address other design tasks. Some of these tasks will not’
> require too much additional

<img src="&#39;./images/&#39;/media/image191.png"
style="width:8.25in;height:0.67986in" />

> programming effort. These include post-processing for functional and
> behavioral simulators, and data-base query Our ultimate goal, however,
> is a natural language interface

<img src="&#39;./images/&#39;/media/image192.jpeg"
style="width:8.25in;height:0.34028in" />

> for our integrated CAD/CAM/CAT environment. A follow-

<img src="&#39;./images/&#39;/media/image193.jpeg"
style="width:8.25in;height:0.34028in" />

> on project, to CLEOPATRA is currently being pursued as described
> below.

<img src="&#39;./images/&#39;/media/image194.jpeg"
style="width:8.25in;height:0.34028in" />

> An Improved Natural Language Interface for CAD

<img src="&#39;./images/&#39;/media/image195.jpeg"
style="width:8.25in;height:0.34028in" />

> T.F. Cobourn, S.W. Director
>
> The purpose of this project is to functionally extend

<img src="&#39;./images/&#39;/media/image196.jpeg"
style="width:8.25in;height:0.34028in" />

> CLEOPATRA. Currently, CLEOPATRA is limited to
>
> operation in the domain of circuit simulation post-processing.

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image197.png"
style="width:8.25in;height:0.67986in" />

> system with interactive graphics. The new interface will be tested on
> designers in industry.

<img src="&#39;./images/&#39;/media/image198.jpeg"
style="width:8.25in;height:0.34028in" />

1.  CONCLUSION’

<img src="&#39;./images/&#39;/media/image199.jpeg"
style="width:8.25in;height:0.34028in" />

> The SRC-CMU research center for CAD has been in existence for four
> years under the directorship of S.W.

<img src="&#39;./images/&#39;/media/image200.jpeg"
style="width:8.25in;height:0.34028in" />

> Director, and has a broad-based program aimed at

<img src="&#39;./images/&#39;/media/image201.jpeg"
style="width:8.25in;height:0.34028in" />

> !aY.!&

<img src="&#39;./images/&#39;/media/image202.jpeg"
style="width:8.25in;height:0.34028in" />

<table>
<tbody>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
<tr>
</tr>
</tbody>
</table>

<img src="&#39;./images/&#39;/media/image203.png"
style="width:8.25in;height:1.7in" />

> PRca

STh’lJDEL

<img src="&#39;./images/&#39;/media/image204.png"
style="width:8.25in;height:0.67986in" />

> Table 1. Computer Aids Developed at CMU

<img src="&#39;./images/&#39;/media/image205.jpeg"
style="width:8.25in;height:0.34028in" />

developing an integrated approach to CAD, CAM and CAT of VLSI circuits
and systems. Special emphasis has been placed on the investigation of
appropriate AI techniques, and

the development of manufacturing-based CAD and

manufacturing-based CAT. A number of tools have already resulted from
these activities; see Table 1. We anticipate the release of a number of
additional tools in the near future as

well a.7 an environment in which these tools wiil communicate with each
other.

Approximately half of the $2.5 million operating budget for the center
comes from the Semiconductor Research

Corporation, The remaining funds, and technical guidance,

come from the National Science Foundation, the Army

Research Office, AT&T Bell Labs, Digital Equipment Corporation, General
Electric, General Motors, Gould, GTE,

Harris Semiconductor, Hewlett-Packard, Hughes Aircraft,

IBM, Intel, ITT, MCC, Northern Telecom, Philips, Raytheon, and United
Technologies.

> ACKNOWLEDGEMENT
>
> This paper is obviously the result of efforts by a large
>
> number of individuals. Two are especially appreciated. Gary York,
> assistant director of the center, compiled most of
>
> the project descriptions. Steve Director, director of the center, was
> responsible for the final editing.
>
> REFERENCES

1.  SW. Director et al., “Integrated CAD, CAM, and CAT of VLSI Circuits
    and Systems: The

> CMU Perspective,”IEEEDesignd Test of
>
> Computers,June 1985.

1.  S.R. Nassif and S.W. Director, “WASIM: A Waveform Based Simulator
    for VLSICs,” Pruc. Int. Conf. 072CAD, ICCAD, November 1985.

2.  A.J. Strojwas, “CMU-CAM System,” IEEE Design d Test of Computers,
    February 1986.

3.  I’. Odryna and A.J. Strojwas, “PROD:A VLSI

> Fault Diagnosis System,” IEEE Designd Test of Computers, December
> 1985.

1.  R. Razdan and A.J. Strojwas, “A Statistical Design Rule Developer,”
    IEEE Trans. on CAD, October 1986.

2.  J.P. Shen et al., “Inductive Fault Analysis of MOS Integrated
    Circuits,” IEEE Design d Test

> of Computers,December 1985.

1.  S.H. Robinson and J.P. Shen, “Towardsa Switch-Level Test Pattern
    Generation Program,”

> Proc. Int.Conf. on CAD, ICCAD, November 1985.

1.  M.L. Bushnell and SW. Director, “VLSI CAD

> ToolIntegrationUsingtheULYSSES
>
> Environment,”Proc. Design AutomationConf.,
>
> DAC, July 1986.

1.  T. Samad and S.W. Director, “Natural Language Interaction for
    Computer-Aided Design -- A First

> Step, ‘1 IEEEDesignd Test of Computers,
>
> August 1985.

889
