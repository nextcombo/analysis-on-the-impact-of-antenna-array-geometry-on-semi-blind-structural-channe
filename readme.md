# Analysis on the Impact of Antenna Array Geometry on Semi-blind Structural Channel Estimation Performance in Large-Scale MIMO-OFDM Systems [with MATLAB Code]

Introduction: Massive MIMO (Multiple Input Multiple Output) is a technology in 5G wireless communication, where a large number of antennas are used at the base station to communicate with multiple user devices simultaneously within the same frequency band. Massive MIMO combines with Orthogonal Frequency Division Multiplexing (OFDM) to achieve numerous benefits in terms of coverage, capacity, spectrum, and energy efficiency [1].
In communication, to accurately recover the source signal, the system must obtain channel state information (CSI). Trained symbols (also known as pilots) are inserted into the data sequence to estimate CSI and synchronization. The length of the pilot sequence should be greater than the number of elements in the antenna array. Due to the large number of antenna elements, channel estimation in massive MIMO systems is very complex and has long training overhead [2].
There are two popular wireless channel models, namely non-structured model and structured model. The non-structured model is widely used due to its simplicity but it does not truly apply to mmWave with several significant reflection waves. This paper studies the semi-blind channel estimation problem in mmWave MIMO-OFDM systems. The semi-blind (SB) channel estimation algorithm is a combination of traditional training-based methods and blind methods. They use several pilot symbols and other types of information [3].
The SB algorithm can effectively reduce the number of pilot symbols while maintaining acceptable accuracy [4]. In the non-structured channel model, each pair of transmitter and receiver antennas is described as a complex gain [5], while the structured model includes complex gains, departure direction (DoD), and arrival direction (DoA). This model is also known as mirror or geometric channel model [5], [6].
In [7], Poormohammad et al. proposed that the geometric shape of an antenna array will inevitably affect the accuracy of DoA and DoD estimations. Furthermore, as the number of antennas increases, a 3D antenna array saves significant installation space compared to both 1D and 2D arrays. Typically, most studies in the literature consider either 1D or 2D antenna array systems. Therefore, this paper analyzes the performance bounds for semi-blind channel estimation within a 3D massive MIMO array structure. For the SB method, aside from the pilot parts, it is assumed that data symbols are i.i.d. and known statistically. Two antenna array structures, namely: uniform linear array (ULA) and uniform cylindrical array (UCyA), are considered. Simulation results show that the UCyA outperforms traditional ULA arrays in terms of SNR and number of elements.
Our contribution in this paper is to derive the Cram'er-Rao bound (CRB) for semi-blind channel estimation in the UCyA structure. Section 2 introduces the structural model of 3D massive MIMO. The CRB biases based on training and SB channel estimation methods in both structured and unstructured models are shown in section 3. Finally, through numerical experiments, the performance of the UCyA structure and its asymmetric counterpart is compared.
Figures in the article
Conclusion This paper utilizes the Cram ′ erRao bound to analyze the impact of antenna array geometry on channel estimation errors in large-scale MIMO-OFDM systems. The CRB for channel estimation under both scenarios, namely, OP and SB-based methods. Simulation results indicate that the structured channel model significantly improves channel estimation performance. The UCyA structure achieves less channel estimation error under this model, and this geometric structure is more suitable than traditional OFDM structures.

## Images

![(Channel Estimation)Analysis on the Effect of Array Geometry on Semi-blind Structural Channel Estimation in Massive MIMO-OFDM Systems [with MATLAB Code]](01.jpg)
![(Channel Estimation)Analysis on the Effect of Array Geometry on Semi-blind Structural Channel Estimation in Massive MIMO-OFDM Systems [with MATLAB Code]](02.jpg)
![(Channel Estimation)Analysis on the Effect of Array Geometry on Semi-blind Structural Channel Estimation in Massive MIMO-OFDM Systems [with MATLAB Code]](03.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
