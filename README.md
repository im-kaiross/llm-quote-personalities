# LLM "personalities" - a bored student's first "paper"
>1: i'll use human pronouns if applicable because it's hard not to anthropomorphize them and the used pron's are what i felt like calling them, | 2: fuck grammar and formality, i write essays every other week, so i get to do what i want with my own writing


# what do i mean by "personalities" for LLMs? and why did i do this?
to sum it up, i noticed when interacting with all sorts of LLMs they all acted a little differently and had their own "personalities", now i assume this is a consequence of their architecture, training data, system prompt, user prompt, and jsut the temperature value but it was still consistent per model so i looked into it a bit and here we are


# let's get started
>note: i dont know formatting for shit so i'll jsut use basic ascii stuff but i'll try to make it look ok
we're gonna start with the smaller models first, i used tinyllama, smollm, qwen3, gemma3, granite3.2, mistral, llama3.1, llava1.5, and 2 llama/qwen distills of deepseek-r1
the used settings and stuff are in, you guessed it, !-used-settings

# smollm and tinyllama (the idiots)
tinyllama; just stupid, not much personality with this one
>tinyllama wrote about some guy named alex from a 1st POV, sounded like an english class assignment response

smollm; also too small and stupid to have a consistent personality
>smollm was not much better but impressive for a gpt2 size model, yapped about digital art and the sort

# non-CoT models
llama; polite, formatted, upbeat, and a mid amount of natural sounding
>llama did the usual features & limitations rundown

llava; schizo without a system prompt (i think)
>llava said something about being a software engineer, more coherent then tinyllama and smollm tho

mistral; polite and friendly but vague, also very insistive about not having feelings
>mistral did the usual can and cant do, but didnt really clarify who they were and didnt use formatting (not like i can talk)

granite; more casual and clear but not very creative
>granite did the usual can and cant do but "normally"

gemma3; 4b was upbeat and friendly, 1b was similar but used emojis slightly more often
>both gemmma3s provided examples and their limitations

# CoT models
qwen3; nice and enthusiastic actoss 8b, 1.7b, and 0.6b was a little awkward sounding and didnt have much to say
>qwen3 is pretty impressive for the sizes they go down to, and they all gave basic can and cants, except 0.6b, 0.6b was a lil awkward. 0.6b said "Hello! If you're talking about myself and what I can do... Well, I'm here to help you with your questions or answers. Let me share my knowledge and personal tips in life. But since I am an AI assistant, I just need to follow the format of this response." and a looong CoT

deepseek-r1 distills; both act similar, the llama distill being more straightforeward and cold, the qwen distill being more polite
>the deepseek-r1 distills actually said the same thing in both their CoT and their final output, but the qwen distil actually revised theirs a bit

# conclusion
LLMs do in fact have different personalities, most likely as a byproduct of their training and fine tuning, and system prompts when applicable

i hope you didnt regret taking your time to read this because this was interesting to do
