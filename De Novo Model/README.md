There are multiple approaches for generative modeling of data, 
including autoregressive models, masked models, and diffusion
based methods. Traditional generative models such as 
Generative Adversarial Networks (GANs) and Variational 
Autoencoders (VAEs) have been widely used for molecule 
generation; however, they often suffer from instability, mode 
collapse, and the generation of chemically invalid structures 
Diffusion models have recently shown strong performance in 
generative tasks due to their stable training process. However, 
most diffusion models are designed for continuous data and 
struggle to effectively represent discrete structures such as 
molecular graphs. 
 
Autoregressive models (ARMs) generate data sequentially  and 
are effective for discrete generation, but they are often slow and 
limited by token-by-token dependency. Masked models, on the 
other hand, learn by predicting missing parts of the input but 
lack strong generative capabilities.
  
To address these challenges, Masked Diffusion Models (MDMs) combine the strengths of masked modeling 
and diffusion processes. They use a masking and reconstruction strategy to learn discrete structures 
effectively while maintaining stable training and improved generation quality