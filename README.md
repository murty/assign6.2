public abstract class instruments()
{
string name;
play();
}
class stringedinstruments extends instruments()
{
int numberofstrings;
}
class electricguitar extends stringedinstruments()
{
electricguitar e=new electricguitar();
e.name ="king";
e.numberofstrings=5;
public void play()
{
system.out.println("no of strings"+e.numberofstrings);
}
}
class electricbassguitar extends stringedinstruments()
{
electricbassguitar b=new electricbassguitar();
b.name ="king";
b.numberofstrings=5;
public void play()
{
system.out.println("no of strings"+b.numberofstrings);
}
}
