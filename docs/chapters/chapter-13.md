# Chapter 13: Measurement Challenges

![Image 13 - Challenge](../images/13.%20Challenge.png)  

## Overview

Unfortunately, evaluating generative AI systems can be a real challenge.  

In traditional ML, data scientists are typically chasing one metric: accuracy. And you can calculate accuracy by dividing the number of correct predictions by the total number of predictions.  

For generative AI, we may also be interested in accuracy—which we can evaluate if we have ground truth.  

But we may also be interested in very different metrics, for more open-ended outputs. For example, we may want to assess whether our model or application outputs are fair, grounded in our source data, or grammatically correct. That’s a little more complex than accuracy.  

We also need good test data. You might already have good test data, like typical questions from your customers and your model’s response to those questions, from your customer service team or another business unit—but you might not have high quality test data for edge cases, like prompts with the latest jailbreaking techniques.  

Another challenge is explainability. To make data-driven development decisions and really debug our system, we need to be able to understand why our model or application scored our model outputs a certain way.

At Microsoft, we needed to figure all of this out so we could systematically evaluate our own copilots before deploying to production.

Now, Azure AI provides a robust toolkit for evaluating generative AI in a repeatable, transparent way.

## Resources and Further Reading

### Online Resources
- 🌐 [Safety Evaluations Transparency Note](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/safety-evaluations-transparency-note)  
- 🌐 [Observability](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/observability)  
- 🌐 [Agent Evaluators](https://learn.microsoft.com/en-us/azure/ai-foundry/concepts/evaluation-evaluators/agent-evaluators)  
 

## Next Steps

Continue your learning journey:

[← Chapter 12](chapter-12.md) | [Chapter 14 →](chapter-14.md)

---

<div class="card">

**Questions or feedback?** Join the discussion on our [GitHub repository](https://github.com/codess-aus/OREDEV-Building-Trustworthy-AI) or connect with the community.

</div>
