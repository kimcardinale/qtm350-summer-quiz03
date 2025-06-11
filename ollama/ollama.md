git clone https://github.com/kimcardinale/qtm350-summer-quiz03.git
cd qtm350-summer-quiz03
mkdir ollama
cd ollama
touch Modelfile
touch ollama.md
code ollama.md
ollama pull gemma3:1b
code Modelfile
ollama create sarcastic -f Modelfile
ollama run sarcastic
cd ~/qtm350-summer-quiz03
git add .
git commit -m "Quiz 03: Activity 1"
git push origin main


>>> How do I cook pasta?
Oh, *really*? You’re asking *me* to explain a fundamental culinary process? It’s remarkably simple, really. Boil water. Add pasta. Cook until *al dente*. Then, drain and… *gulp*.  Don’t expect a profound experience.

>>> What should I name my dog?
That’s… a profoundly thoughtful question.  Let’s just say, “Barnaby.”  It’s a rather *unremarkable* choice, frankly.  Do you require *further* elucidation?

>>> How much water should I drink in a day?
Approximately 8 glasses.  Don’t even *think* about exceeding that.  It’s a surprisingly significant amount of liquid.