<div class="a-content">

<div class="m-step-header">

<div class="body">
<div class="u-clearfix">
<div data-react-component-path="components/Application/sections/Steps/Article">
<div data-hypernova-key="componentsApplicationsectionsStepsArticle" data-hypernova-id="4913b634-86e5-4893-b2c7-41fa25002221">
  <div><div class="spacer-module_default__3N2H9 spacer-module_bottom-5__35eKR"><div>
    <img srcset="https://ugc.futurelearn.com/uploads/images/f0/03/small_hero_f003d136-5d97-426b-b905-6eb5795ec55e.png 320w, https://ugc.futurelearn.com/uploads/images/f0/03/hero_f003d136-5d97-426b-b905-6eb5795ec55e.png 648w, https://ugc.futurelearn.com/uploads/images/f0/03/large_hero_f003d136-5d97-426b-b905-6eb5795ec55e.png 729w, https://ugc.futurelearn.com/uploads/images/f0/03/large_hero_f003d136-5d97-426b-b905-6eb5795ec55e.png 2x" sizes="(min-width: 1695px) 729px, (min-width: 680px) 648px, 320px" alt="An icon of a network with seven nodes, that are red circles connected by white lines." src="https://ugc.futurelearn.com/uploads/images/f0/03/hero_f003d136-5d97-426b-b905-6eb5795ec55e.png"></div><div class="align-module_wrapper__1Fi9D align-module_sBreakpointDirectionhorizontal__2VAJs">
    <div class="align-module_itemsWrapper__utBam align-module_sBreakpointSpacing2__1ZJc7 align-module_sBreakpointAlignspaceBetween__3Yfrh align-module_wrap__kOYRr">
      <div class="align-module_item__oiojU">
 <p>The type of machine learning algorithm we were using when doing regression with RapidLib is a neural network. Understanding neural networks will give you some useful insights as we go forward, however, don’t be too concerned if this all seems double dutch. You will be perfectly able to continue with the course.</p>

<p>In much the same way that, when people talk about AI, they’re often talking about machine learning, when people talk about machine learning, they’re often talking about neural networks. Or to give them their full title: artificial neural networks.</p>

<p>This is to distinguish them from biological neural networks, or to give them their full title: brains. Artificial neural networks are loosely based on brains and sit in the category of machine learning approaches that are known as biologically inspired. However, the size and complexity of the networks and their constituent parts are considerably lower than that of a human brain. The current tip-top-state-of-the-art approaches are considered roughly analogous to the brains of worms or ants.</p>

<p>These techniques have been around for decades and have recently been enjoying a renaissance. Countless books, PhD theses and patent applications are filled with information about them and below we will attempt to cover the absolute basics in a few paragraphs. Understanding this will give you some useful insights as we go forward, however, don’t be too concerned if this all seems double dutch. You will be perfectly able to continue the course regardless.</p>

<h2 id="neurons">Neurons</h2>
<p>The building blocks of a network is a neuron. As demonstrated in the diagram, this is a single unit that takes a number of inputs and multiplies each by a given weight. In a common implementation, these are then added up together and the result is outputted. Again, these are inspired by neurons in actual brains.</p>

<p><img src="https://ual-cci.github.io/futurelearn/ML_4_neuron.png" alt="inputs 1, 2, and 3, labelled x weight 1, 2, and 3, are arrows pointing to a circle with a plus. This leads to a rectangle that says Activate Function with a curved line on it, leading to an output."></p>

<p>Some neurons even connect their own outputs back into themselves, with this feedback loop giving each neuron a kind of memory. They are truly the Jimmy Hendrix of the machine learning world.</p>

<h2 id="networks">Networks</h2>
<p>We can build a bunch of these neurons and chain them together in various ways to make more complex models. One common approach is to have the inputs going into multiple different neurons, each applying their own weights. They are then re-combined to produce the output. You can also have outputs from one neuron serving as input to another neuron. These are known as hidden layers and the network in the diagram below has two.</p>

<p><img src="https://ual-cci.github.io/futurelearn/ML_4_network1.png" alt="A greyscale diagram of a nine node network of circles with two (input), three, three, and one (output) circles. The two rows of three circles are labelled Hidden Layers."></p>

<h2 id="training">Training</h2>
<p>Once the network’s structure has been decided, we then need to take our dataset and use it to produce a model that is able to generalise to the relationships within it. We do this by adjusting the weights. Often randomly initialised, it is the weights that will decide what output is calculated by a given input.</p>

<p>During the training process, we take our known inputs and run them through the model to get an output. Unless we have been unfathomably lucky, this will not be the same as the expected output in the dataset. We can use the information about how close we were to the correct answer to adjust the weights in a way that will hopefully move us closer.</p>

<p>We do this for every input-output pair in the dataset, then start again. This is often done hundreds or thousands of times, gradually improving each time. The rationale is that if we can train a model to work well with known examples, when it sees new examples it will be able to respond appropriately. This goal is achievable depending on the complexity of the problem and the size and quality of our dataset.</p>

<h2 id="depth">Depth</h2>
<p>With a metaphor that is surprisingly malleable, in the same way we might describe a person who possesses depth as having many hidden layers, the same goes for networks. When you hear of deep learning and deep networks, this means a network with a large amount of hidden layers. I suggested Onion Networks at the convention but was shouted down. I’m not bitter, these things are basically just a popularity contest anyway <br>      ¯\ _(ツ)_/¯.</p>

<p>Although these are <em>de rigueur</em> and powerful, we won’t really cover networks of this size in this course for a number of reasons. Primarily, the computational time and power to train and run these data-hungry networks is untenable. We want to be able to train models on our reasonably resourced laptops and don’t want to spend all our time waiting for hours / days / weeks / months for a model to train.</p>

<p>There is a torrent of fun stuff you can get done with smaller networks and smaller datasets. This means you get to spend time developing and using your models with datasets you’ve collected yourself. It’s through this quick cycle of hands on testing and tinkering that you’ll build an intuition for how to use machine learning and data to realise your creative goals.</p>

<p>In fact, the default size of a network in RapidLib is one hidden layer with the number of hidden nodes equal to the number of inputs, which in this case is one. As you’ll see in the next activity, this is plenty powerful to start building expressive instruments. You can build more expansive networks with RapidLib, and we’ll experiment with that in the next step.</p>

<p>Do you think modelling biological systems is a good way to build AI systems? Do you know of any other examples?</p>
</div><div><p>© Creative Computing Institute</p>


</div>
</div>
</div>
