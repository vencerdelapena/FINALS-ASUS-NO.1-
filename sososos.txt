#include <iostream>
using namespace std;
int main ()

{
	string name;
	cout << "Enter your character name" <<endl;
	cin >> name;
	cout << "Hello "<<name<<" !" <<endl;
	cout << "Welcome to PRISON ESC! \n\n";
	cout << "Please follow the directions \nUse only Capital letters\nInput an appropriate answer \nOnce you've picked the wrong choice, the game will end \nDON'T MAKE ANY MISTAKES! \n\n";
	cout << "The poor man was imprisoned because he stole a ring for his beloved girlfriend.\n";
	cout << "He wants to break from the prison to attend their most awaited/anticipated 5th\nanniversary.\n";
	cout << "And its tomorrow. His girlfriend was from abroad so she didn't know that the manis imprisoned. \n\n" ;
	cout << "In the prison there is bed, drawer, comfort room and ferric chloride. \n\n" ;

	char A, B, C, D, E, F, G, H, I;
    cout << "A: Go to bed \nB: Got to drawer \nC: Go to the comfort room \nD: Get the ferric Chloride \n\n";
    cin >> A;
        {
            if (A == 'A')
                {
                    cout << "\nYou fell asleep and the day of the anniversary has passed.\n\n\n";
                    cout << "Sad end.\n\n";
                }

            if (A == 'B')
                {
                cout << "\nThe drawer has a notebook in it. The notebook says: \n\n" ;
                cout << "-Dear fellow prisoner, I've gained knowledge and attempted to escape many times, I'll let you know my secret but first solve my riddle.--\n\n" ;
                cout << "I am water, fire gives me strength.\nI hold the earth, I hold the water and beauty rises from me. What could be the answer?\n\n" ;
                cout << "A. Glass Bottle \nB. Flower Pot \nC. Jar\n\n";
                cin >> B;

                if (B == 'A')
                    {
                    cout << "\nWrong.\n";
                    }
                if (B == 'B')
                    {
                    cout <<"\nThe flower pot was placed on the top left window which you can't reach. In orderto reach it, you have to move the bed to the bottom of the window\n";
                    cout <<"A: Move the bed to the left \nB: Move the bed to the right\n\n";
                    cin >> C;

                    if (C == 'A')
                        {
                        cout << "\nYou moved the bed to the left.\n";
                        cout << "You got the flower pot, it has a YELLOW flower on it and a letter says 'RAINBOW FROM TOP TO BOTTOM'. You dug the flower pot and found 3 keys labeled 1, 2, and 3\n\n\n\n";
                        cout << "A day has passed and its the man anniversary with his gf.\n";
                        cout << "He need to break out to the prison today. Each keys are coated of some sort of \nbrown material. You read the notebook again. On the second page it says:\n\n";
                        cout << "--I'm not very nice so one of the keys is the way to get out of your cell. \nYou have to do some methods and electronic knowledge about this. You need to \nblacken the coated key using a pentel pen and dip the key on the ferric chloride.--\n\n";
                        cout << "The guard gave you food for the day. He enters the cell and gave the plate and aplastic cup with water. He dropped a pentelpen.\n\n";
                        cout << "A: Give back the pen \nB: Keep the pen\n\n";
                        cin >> D;

                        if (D == 'A')
                            {
                            cout <<"\nYou gave the pen.\nYou waited to long for the guard to come back since you need the pen and the dayof the anniversary passed.";
                            }
                        if (D == 'B')
                            {
                            cout <<"\nYou kept the pen.\n";
                            cout <<"You now have the choice which to blacken, key no. 1, 2 or 3. Since the ferric \nchloride you saw is good for one key only. You have to pick one.\n\n";
                            cout <<"A: Key No. 1 \nB: Key No. 2 \nC: Key No. 3\n\n";
                            cin >> E;

                            if (E == 'A')
                                {
                                cout <<"\nThe day has passed since you got the wrong key \n\nSad End.\n\n";
                                }
                            if (E == 'B')
                                {
                                cout <<"\nThe day has passed since you got the wrong key \n\nSad End.\n\n";
                                }
                            if (E == 'C')
                                {
                                cout <<"\nYou blacken the key with the pentel pen.\n";
                                cout <<"You grabbed the plastic cup and pour the ferric chloride into it. You put the \ncorrect key and let it sit in there.\n";
                                cout <<"Few minutes later, you washed the key to the toilets water and the brown \nsubstance came off.\n";
                                cout <<"You put the key in the keyhole and you've exit the prison cell.\n\n\n\n";
                                cout <<"3pm, the time would be 6pm in the some sort of restaurant.";
                                cout <<"You read th notebook again it says --At 3pm all of the guards is on their offices and the outer guardsare conducting a meeting too on the main office so no one is around at 3pm to \n4pm. One more tip, KEEP RIGHT BROTHER.--";
                                cout <<"It's guards break time so most of the \nguards are in their offices. Fortunately, the cctvs are on repair through the \nexit. You've encounter 3 doors, one of the doors is correct.\n\n";
                                cout <<"A: Left Door \nB: Middle Door \nC: Right Door\n\n";
                                cin >> F;

                                if (F == 'A')
                                    {
                                    cout <<"\nLeads to the rooftop. You've been seen by the tower security.\n\nYou got Busted.\n\n";
                                    }
                                if (F == 'B')
                                    {
                                    cout <<"\nLeads to the cafeteria, inmates are not allowed in this area at 3pm.\nYou got Busted.\n\n";
                                    }
                                if (F == 'C')
                                    {
                                    cout <<"\nLeads to the exit door.\n";
                                    cout <<"You go to the path and the guards is done with their break, its past 3:30 you \ngot 2hrs and 30 mins left. The guards starts their duty and roam the area.\n";
                                    cout <<"You heard someone is walking by on the left side.\n\n";
                                    cout <<"A: Run to the right \nB: Hide to the bathroom\n\n";
                                    cin >> G;

                                    if (G == 'A')
                                        {
                                        cout <<"\nYou got caught and tased.\nYou got Busted.\n\n\n";
                                        }
                                    if (G == 'B')
                                        {
                                        cout <<"\nYou hid to the bathroom and came out after the guard walk by.\n";
                                        cout <<"You go to the right side and see the guard sleeping on the desk, you saw a taseron the table and picked it up.\n";
                                        cout <<"Going to the right path you've encounter a guard on the path, he didn't see you.\n";
                                        cout <<"A: Run \nB: Hide in the Bathroom \nC: Use the taser when he walk by.\n\n";
                                        cin >> H;

                                        if (H == 'A')
                                            {
                                            cout <<"\nYou got caught and tased.\nYou got Busted.\n\n\n";
                                            }
                                        if (H == 'B')
                                            {
                                            cout <<"\nYou hide on the bathroom but the guard was going to take a piss and saw you.\nYou got Busted.\n\n\n";
                                            }
                                        if (H == 'C')
                                            {
                                            cout <<"\nYou used the taser and got the guard unconscious.\n";
                                            cout <<"You picked up his keys, id's, his glasses and uniform to disguise and got passed the prison guards easily.\n\n\n\n";
                                            cout <<"4pm its a 2hr trip from the prison to the meeting place so you need a car.\nThe keys you've picked up is for the 3 cars outside.\nIts from the visitors of the prisoners that have been handed to the guard.\n";
                                            cout <<"You looked on each cars:\nCar 1 doesn't have anything on it, you also see that the fuel bar is kinda wore down \nCar 2 you've seen some clothing and IDs\nCar 3 It has a full tank fuel on it plus its luxurious. It also have some \nclothing and IDs.\n\n";
                                            cout <<"A: Car No. 1 \nB: Car No. 2 \nC: Car No. 3\n\n";
                                            cin >> I;

                                            if (I == 'A')
                                                {
                                                cout <<"\nYou got caught on the guard post.\nYou got Busted.\n\n\n";
                                                }
                                            if (I == 'B')
                                                {
                                                cout <<"\nYou picked up and dress yourself and showed the IDs on the guard post. \nYou exited the prison.\n";
                                                cout <<"You got to your date and your gf was very happy. \nShe said that she didn't need any gifts, all she needs is his presence on \nthat day.\n\nTHE END\nTHANK YOU FOR PLAYING!!!!\n";
                                                cout <<"Created by: Opao, Kennard \nAbillar, Theresa \nLadao, John Aeron \nDela Pena, Vencer";
                                                }
                                            if (I == 'C')
                                                {
                                                cout <<"\nYou picked up and dress yourself and showed the IDs on the guard post.\nThe car was very popular and the authority notices the car. You have beenchased by the police cars.\nYou ended up over speeding and hit the side barriers, the car flipped and \nexploded.\n\n YOU DIED.\n Bad End\n\n\n";
                                                }
                                            }
                                        }
                                    }
                                }
                            }
                        }
                    if (C == 'B')
                        {
                        cout << "\nYou moved the bed to the right. Nothing happened\n";
                        cout << "Game end.\n\n";
                        }
                    }
                if (B == 'C')
                    {
                    cout << "\nWrong.\n";
                    }
                }

            if (A == 'C')
                {
                cout << "\nYou entered the bathroom.\n" ;
                cout << "You accidentally slipped head first, and got amnesia. \n\n\n" ;
                cout << "Sad End. \n\n" ;
                }

             if (A == 'D')
                {
                cout << "\nYou reached the ferric chloride.\n";
                cout << "You got extremely depressed and drank the whole bottle. \n\n\n" ;
                cout << "Bad End. \n\n" ;
                }

        }
        return 0;
}


