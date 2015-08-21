# Instruction

## Read and understand the code, the logic behind it, the limitation of it
* Revise the code such that it consists of three addition functions, input, process and output, put your commit number below.
* Revise the code such that it can accept input from command line, put your commit number and answer question 1 below


## Revision, put your commit number here :4d22224e0e6f62860025a3100f4dcb5b5f407cbd
* Three functions:
public void input(){

				int[] input = { 4, 5, 2, 8, 9, 1, 2, 4, 3, 1 };
			}

public void process(){
            while (flag)
            {
                flag = false;
                for (int i = 0; i != input.Length - 1; i++)
                {
                    if (input[i] > input[i + 1])
                    {
                        int temp = input[i];
                        input[i] = input[i + 1];
                        input[i + 1] = temp;
                        flag = true;
                    }
                }
            }
			}

public void output(){
            for (int i = 0; i != input.Length; i++)
            {
                Console.Write(input[i]);
                Console.Write(" ");
            }
            Console.ReadKey();
			}


* Get input from command line: 

Console.Write("how many number");
int j = Convert.ToInt32(Console.ReadLine());
for(int i = 0;i<j;i++)
{
int input[i] = Convert.ToInt32(Console.Readline());
}

## Questions
1. What are the limitations of your new code?

Answer: this program is sort interger it can sort only real number