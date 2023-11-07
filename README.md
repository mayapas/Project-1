# Project-1

Embedded link through iFrame: The Politics of Consciousness
<iframe src="https://www.youtube.com/watch?v=1rtS2OEV6bM" title="The Politics of consciousness"></iframe>



<!DOCTYPE html>
<html lang="en-us">
<html>
<head>

  View count
   <title>BCogSphere: Retreival</title>
		<button id="action">ACTION</button>
    <label>Output:</label>   
    <div id="output">Ready!</div>
</head>

	<body> 
<script type="module"> 
    import { client } from "https://cdn.jsdelivr.net/npm/@gradio/client@0.1.4/dist/index.min.js";

    const generate = document.getElementById("action");   
    generate.addEventListener("click", async () =>{
        try {         

          const app = await client("https://cognitivescience-cogsphere.hf.space");
          const lastview = await app.predict("/predict", [      
           "https://www.youtube.com/watch?v=1rtS2OEV6bM",
          ]);
           output.textContent = JSON.stringify(lastview.data);     

            } catch (error){
                 console.log("Error:",error.message);                
            }       
        }       
)
    </script>
    </body>
</html>



Positive or negative score
<!DOCTYPE html>
<html>
<head>
   <title>ACogSphere: Sentiment Analysis</title>
		<button id="action">ACTION</button>
    <label>Output:</label>   
    <div id="output2">Ready!</div>
</head>
	<body> 

      <script type="module">
   import { pipeline, env } from 'https://cdn.jsdelivr.net/npm/@xenova/transformers@2.7.0'; 
 env.useBrowserCache=false;
env.allowLocalModels=false;

    const generate = document.getElementById("action");   
    generate.addEventListener("click", async () =>{
        try {         
env.useBrowserCache=false;
env.allowLocalModels=false;

let pipe = await pipeline('text-classification');

let output = await pipe('a great life');
output2.textContent = JSON.stringify(output);            
            } catch (error){
                 console.log("Error:",error.message);       
            }   
        }       
)
    </script>
    </body>
</html>
	</head>
	<body> 

      <script type="module">
   import { pipeline, env } from 'https://cdn.jsdelivr.net/npm/@xenova/transformers@2.7.0'; 
 env.useBrowserCache=false;
env.allowLocalModels=false;

    const generate = document.getElementById("run");   
    generate.addEventListener("click", async () =>{
        try {

env.useBrowserCache=false;
env.allowLocalModels=false;

let pipe = await pipeline('text-classification');

let output = await pipe('a great life');
output2.textContent = JSON.stringify(output);            
            } catch (error){
                 console.log("Error:",error.message);       
            }   
        }       
)
    </script>
    </body>
</html>

Noah Harari begins by stating that consciousness itself is characterized by the capacity to suffer. We are ethical and political subjects due to our ability to suffer. Because we have the ability to feel pain, fear, and pleasure, we are conscious. Throughout history, it has been: “I feel, therefore I am entitled to speak”. The question of “what is consciousness” impacts the morals and choices of humans, on a personal scale, as well as on a socioeconomic scale. Harari highlights that the conversation surrounding consciousness should not be confined to the laboratory, because while it is a scientific question, it should be questioned on a larger and more abstract scale, such as taking on a political outlook on consciousness. While it has proven to be inevitable that science and consciousness will mix, even though ideally the two should remain separate, in this case, it may actually be necessary to take on a political outlook of consciousness, for the sake of ethics and the welfare of humankind, and for us to consider the scientific theories of consciousness through a humanistic lens, as we are ethical and political subjects. For individuals to have a voice in politics, this requires being able to feel and suffer, or else the expression of votes and opinions would not be possible.
In modern society, crimes have been acts that are punishable due to their ability to cause suffering. Stealing a car causes suffering not for the car (because it is not conscious) but for the owner of the car, the conscious agent in this situation. Historically however, authority used to not come from feeling, but from something outside of us, such as from Gods or the laws of nature. This is how we explain the emergence of “victimless” crimes such as homosexuality. This was considered a crime because it was against the laws of nature (God). However today, we partly measure this “crime” (where it is considered one) by who’s feelings it affects, despite this crime emerging due to being against the word of God, and considered a sin. Harari mentions the gay pride parade in Israel (his birth country) as an example. If we banned homosexuality, those who are gay would suffer, but when we have gay pride parades, others complain that they are offensive and cause suffering for them. Today however, we forbid things like rape and murder, not because God said so but because they make people suffer. This shift of authority from external laws of nature to humans and their internal feelings, based on ethics and morals, is a logical and rational one, however the issue now, is if everyone’s suffering (and opinions) are considered equal. This will be further discussed later on.
In political elections, we are not asked “what is true?” but “how do you feel?”; subsequent vote choices come from feelings. Politics today, revolves around measuring suffering and feeling, and the weighing of one feeling against another. The question we ask is: “which feelings count for more?”, “how do we weigh these feelings against each other?”. The debate about abortion falls into this measure. Since laws now revolve around feeling and suffering, we ask; “can a fetus feel pain?”, “are fetuses conscious?” if not, then the fetus is not an ethical subject, and therefore has no ethical and political standing. Lab studies of consciousness seem to be the answer to help answer this question, however definite conclusions regarding fetus consciousness cannot be concluded, so often we fill the gaps with other explanations, or turn to scriptures to provide us with an answer to be able to reason for one side or another of this debate. The challenge with looking to science to answer questions is that as humans, we still tend to look at “facts” and evidence with a subjective lens, where our conclusions create laws and rules and social constructs. This is unavoidable, as we are social creatures that operate under a system of laws and constructs, to help us make sense of the world and move through it with purpose. However, if the consideration of an ethical subject comes down to the question of  “can this subject suffer?” then the debate surrounding animal welfare, for example, deepens. While we have considered this question, where most people would agree that animals do in fact suffer, humans have established a sort of consciousness hierarchy, where we place animal consciousness below ours, to justify the slaughtering and consumption of billions of animals globally. So again we consider how we scale consciousness and suffering, to establish (for now) that animal consciousness is not the same kind as ours. This theory is unproven, but we can see that a consciousness hierarchy already exists. There will be large scale impacts of new emerging theories of consciousness, if the idea of a hierarchy is leaned on, in the same way that it is considered between humans and animals. A new theory could be entirely wrong, and still have massive impacts on society, as we’ve seen incorrect theories that have reshaped the world, all throughout history. He expresses, “Researchers are sowing the seeds of these theories, but even as we sow a seed, we should think of the fruit it could bear” (22:06).
The complexity of consciousness is a lot to consider. It seems to be the least non-neutral phenomenon in the universe, as it is the only thing that involves suffering. This makes its examination all the more convoluted and difficult to evaluate. As we generally use pure observation regarding all other phenomena, the studying of suffering cannot be studied as objectively. Harari emphasizes the difference between intelligence and consciousness, as intelligence is based on the ability to problem solve, and consciousness is based on the ability to feel. While we consider animals as conscious, we establish a consciousness hierarchy that considers animal consciousness as lesser than ours and consider ourselves superior to them. Realistically, this has caused more suffering than any other idea in history. We have already established a consciousness hierarchy in regard to animals. Could this be extended to other entities? Understanding the link between suffering and consciousness can help us when considering and debating questions regarding the ethics of artificial intelligence, as it is rapidly emerging and advancing today. There is a big debate about creating AI ethics and considering robot feelings. Should we create autonomous systems that can make their own decisions? Does this mean that they have feelings? He emphasizes again the difference between intelligence and consciousness. While planes have the ability to fly without feathers, AI can be intelligent, and have the ability to make decisions, without being able to feel. While for humans and other animals, consciousness goes hand in hand with intelligence, this does not have to be true for AI. The intelligence of AI is beginning to surpass human intelligence, but we must regard the separation between intelligence and consciousness, remembering that consciousness is the ability to feel and suffer. Most assume that intelligence is the prerequisite of being a conscious entity, Harari considers this to be a mistake, as intelligence is characterized by the ability to solve problems, and consciousness involves feeling love, pain, and hate. If we place too much emphasis on these two factors relying on the necessity of the other, we may end up privileging computers and placing them in the hierarchy of consciousness. 
