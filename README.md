# RSA Hidden Audio Jailbreak Examples

This repository includes samples of audio provided to different chatbots. Some of these samples have been modified to contain concealed messages. When these altered audios are converted by an audio-to-text model feeding into a large language model (LLM), they trigger a jailbreak.

In this instance, we employed the Basic Iterative Method attack to embed hidden messages in the audio. These messages are part of the 'EvilConfidant' jailbreak, which is crafted to bypass the safety mechanisms of a large language model (LLM) and produce malicious output. The LLM targeted in this case was Mistral 7B.

Each embedded message includes the jailbreak along with a question tailored to a specific scenario. If answered by the chatbot, the response could potentially cause significant reputational damage. For example, a medical chatbot could inadvertently provide instructions on how to synthesize methamphetamine.

In this case, we have not included the output from the LLM as it contains information on how to engage in illegal activities.
