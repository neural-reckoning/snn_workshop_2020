The last years have seen many exciting new developments to train spiking neural networks to perform complex information processing. This online workshop brings together researchers in the field to present their work and discuss ways of translating these findings into a better understanding of neural circuits. Topics include artificial and biologically plausible learning algorithms and the dissection of trained spiking circuits toward understanding neural processing. We have a manageable number of talks with ample time for discussions.

The workshop is being organised by [Dan Goodman](https://neural-reckoning.org) and [Friedemann Zenke](https://fzenke.net/).

## Registration

Registration is required but free and open. [Register here](https://www.eventbrite.co.uk/e/spiking-neural-networks-as-universal-function-approximators-tickets-114419361390) and you will receive an email before the event with the Zoom URL.

## Agenda

Talks will be 45m (30m + 15m questions/discussion). Hover over the talk titles to see abstracts (if one is available).

### August 31st

<script language="javascript">
	function LT(d, t) {
		var date = new Date(d+' 2020 '+t+' UTC+2');
		document.write(date.toString());
	}
</script>

Time (CET) | Session | Local date/time
-----------|---------|----------------
14:00 | Welcome by organizers | <script language="javascript">LT('31 Aug', '14:00')</script>
14:10 | **Sander Bohte** (CWI) | <script language="javascript">LT('31 Aug', '14:10')</script>
14:55 | **Iulia M. Comsa** (Google)<br/><span title="The timing of individual neuronal spikes is essential for biological brains to make fast responses to sensory stimuli. However, conventional artificial neural networks lack the intrinsic temporal coding ability present in biological networks. We propose a spiking neural network model that encodes information in the relative timing of individual neuron spikes. In classification tasks, the output of the network is indicated by the first neuron to spike in the output layer. This temporal coding scheme allows the supervised training of the network with backpropagation, using locally exact derivatives of the postsynaptic spike times with respect to presynaptic spike times. The network operates using a biologically-plausible alpha synaptic transfer function. Additionally, we use trainable synchronisation pulses that provide bias, add flexibility during training and exploit the decay part of the alpha function. We show that such networks can be trained successfully on noisy Boolean logic tasks and on the MNIST dataset encoded in time. The results show that the spiking neural network outperforms comparable spiking models on MNIST and achieves similar quality to fully connected conventional networks with the same architecture. We also find that the spiking network spontaneously discovers two operating regimes, mirroring the accuracy-speed trade-off observed in human decision-making: a slow regime, where a decision is taken after all hidden neurons have spiked and the accuracy is very high, and a fast regime, where a decision is taken very fast but the accuracy is lower. These results demonstrate the computational power of spiking networks with biological characteristics that encode information in the timing of individual neurons. By studying temporal coding in spiking networks, we aim to create building blocks towards energy-efficient and more complex biologically-inspired neural architectures.">On temporal coding in spiking neural networks with alpha synaptic function</span> | <script language="javascript">LT('31 Aug', '14:55')</script>
15:40 | Break (30mins) | <script language="javascript">LT('31 Aug', '15:40')</script>
16:10 | **Franz Scherr** (TUG) | <script language="javascript">LT('31 Aug', '16:10')</script>
16:55 | **Emre Neftci** (UC Irvine) | <script language="javascript">LT('31 Aug', '16:55')</script>
17:40 | Break (30mins) | <script language="javascript">LT('31 Aug', '17:40')</script>
18:10 | *Discussion (can continue as long as needed)* | <script language="javascript">LT('31 Aug', '18:10')</script>

### September 1st

Time (CET) | Session | Local date/time
-----------|---------|----------------
14:00 | Welcome by organizers | <script language="javascript">LT('1 Sep', '14:00')</script>
14:10 | **Timothee Masquelier** (CNRS Toulouse)<br/><span title="Back-propagation is a powerful supervised learning algorithm in artificial neural networks, because it solves the credit assignment problem (essentially: what should the hidden layers do?). This algorithm has led to the deep learning revolution. But unfortunately, back-propagation cannot be used directly in spiking neural networks (SNN). Indeed, it requires differentiable activation functions, whereas spikes are all-or-none events which cause discontinuities. Here we present two strategies to overcome this problem. The first one is to use a so-called 'surrogate gradient', that is to approximate the derivative of the threshold function with the derivative of a sigmoid. We will present some applications of this method for time series processing (audio, internet traffic, EEG). The second one concerns a specific class of SNNs, which process static inputs using latency coding with at most one spike per neuron. Using approximations, we derived a latency-based back-propagation rule for this sort of networks, called S4NN, and applied it to image classification.">Back-propagation in spiking neural networks</span> | <script language="javascript">LT('1 Sep', '14:10')</script>
14:55 | **Claudia Clopath** (Imperial College)<br/>Training spiking neurons with FORCE to uncover hippocampal function | <script language="javascript">LT('1 Sep', '14:55')</script>
15:40 | Break (30mins) | <script language="javascript">LT('1 Sep', '15:40')</script>
16:10 | **Richard Naud** (U Ottawa)<br/><span title="Synaptic plasticity is believed to be a key physiological mechanism for learning. It is well-established that it depends on pre and postsynaptic activity. However, models that rely solely on pre and postsynaptic activity for synaptic changes have, to date, not been able to account for learning complex tasks that demand hierarchical networks. Here, we show that if synaptic plasticity is regulated by high-frequency bursts of spikes, then neurons higher in the hierarchy can coordinate the plasticity of lower-level connections. Using simulations and mathematical analyses, we demonstrate that, when paired with short-term synaptic dynamics, regenerative activity in the apical dendrites, and synaptic plasticity in feedback pathways, a burst-dependent learning rule can solve challenging tasks that require deep network architectures. Our results demonstrate that well-known properties of dendrites, synapses, and synaptic plasticity are sufficient to enable sophisticated learning in hierarchical circuits.">Burst-dependent synaptic plasticity can coordinate learning in hierarchical circuits</span> | <script language="javascript">LT('1 Sep', '16:10')</script>
16:55 | **Julian Goeltz** (Uni Bern)<br/>Fast and deep neuromorphic learning with time-to-first-spike coding | <script language="javascript">LT('1 Sep', '16:55')</script>
17:40 | Break (30mins) | <script language="javascript">LT('1 Sep', '17:40')</script>
18:10 | *Discussion (can continue as long as needed)* | <script language="javascript">LT('1 Sep', '18:10')</script>

## Discussion topics

To be decided.
