https://beam.apache.org/get-started/quickstart-java/

mvn archetype:generate `
  -D archetypeGroupId=org.apache.beam `
  -D archetypeArtifactId=beam-sdks-java-maven-archetypes-examples `
  -D archetypeVersion=2.42.0 `
  -D groupId=org.example `
  -D artifactId=word-count-beam `
  -D version="0.1" `
  -D package=org.apache.beam.examples `
  -D interactiveMode=false
   
cd .\word-count-beam

dir .\src\main\java\org\apache\beam\examples

In the word-count-beam directory, create a file called sample.txt. Add some text to the file. For this example

mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
 -D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner

ls counts*
   
more counts*

Output :

translate: 1
blown: 1
revengeful: 1
tend: 1
Love: 1
seeing: 1
distracted: 1
like: 2
your: 13
Will: 3
suffers: 1
Prince: 1
court: 1
death: 2
majesties: 1
encounter: 1
restore: 1
purpose: 1
resolution: 1
bourn: 1
returns: 1
enough: 2
quiet: 1
inclined: 1
turbulent: 1
after: 2
sleep: 5
variable: 1
t: 3
God: 2
espials: 1
right: 1
into: 1
reply: 1
wish: 3
awry: 1
humbly: 1
neglected: 2
plastering: 1
she: 1
rich: 1
the: 40
which: 2
you: 29
Rich: 1
down: 2
ha: 1
expectancy: 1
well: 8
Exeunt: 3
very: 1
Ha: 1
delights: 1
wisdom: 1
OPHELIA: 15
home: 1
harshly: 1
objects: 1
all: 10
SCENE: 1
scholar: 1
brains: 1
could: 1
CLAUDIUS: 9
some: 2
shall: 11
pious: 1
already: 2
may: 6
hath: 1
cause: 2
troubles: 1
off: 1
marry: 3
office: 1
He: 1
state: 2
ll: 3
sooner: 1
lordship: 1
accuse: 1
dream: 1
believe: 3
HAMLET: 13
they: 3
himself: 4
dread: 1
Sweet: 1
drift: 1
conference: 1
heard: 2
though: 1
coil: 1
Are: 1
confine: 1
those: 2
thing: 1
devil: 1
once: 1
many: 1
What: 3
receive: 2
wonted: 1
myself: 2
hear: 4
virtue: 1
Whether: 1
merit: 1
longed: 1
thoughts: 1
spurns: 1
commerce: 1
players: 1
time: 3
imagination: 1
We: 7
lash: 1
lord: 11
ones: 1
sounded: 1
life: 2
Could: 1
cannot: 1
ladies: 1
ourselves: 2
power: 1
monsters: 1
confess: 1
feature: 1
smart: 1
kind: 1
house: 1
again: 2
put: 1
day: 1
discourse: 1
visage: 1
Like: 1
aloof: 1
love: 4



































