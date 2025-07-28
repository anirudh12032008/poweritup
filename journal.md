POWER IT UP
author: "Anirudh Sahu"This is my custom battery charging station that can charge up to 8 batteries at once! It uses TP4056 and switches for each 5V power supply and battery holders I'm building it on a veroboard because its wayy eassy and I can modify stuff later to add more slots"
created_at: "2024-07-28"
Time spent - 7 HR

## July 28 - Created schematic, PCB and BOM
so I have created projects with 2s 3s but now I couldnt charge them I was having too many of the battery lying everywhere waiting for there turn to charge up. so yeah I started with creating this project

I started working on selecting which components to use I searched for chips to charge 2s and 3s battery set but they were costly and also unavailable from most of the places so I had no choice other then to just use the tp4056 with single battery use

sthen I tarted with creating the schematic
<img width="700" height="490" alt="4" src="https://github.com/user-attachments/assets/ca08e66b-391d-46cf-b8ba-7985caa65cfd" />

then started desgining the pcb and it was all done 
<img width="884" height="503" alt="1" src="https://github.com/user-attachments/assets/b53c4768-9ca1-4858-ba44-a30887c54a0c" />
then I realised I have missed the IN+ because Idk why I was notified by DRC checks so then I added that too
<img width="764" height="491" alt="3" src="https://github.com/user-attachments/assets/9eb2986e-002b-472e-a9d7-794ea6fed50a" />
<img width="937" height="518" alt="2" src="https://github.com/user-attachments/assets/7a09426f-81ee-41f6-aea8-87cd8e419862" />

Time Spent - 4 Hr

## July 28-29(midnight session) - worked on the case and optimize BOM
so I started with the case and it was a bit laggy to rotate the tp4056 idk why I tried to use something else but still the same issue so it took some time then I added all the stuff in the render and made it look cool the issue again came with the switch placement but I used rocket switch near each battery terminal to make it look great from outside also
<img width="1366" height="418" alt="power up v3" src="https://github.com/user-attachments/assets/ac528b91-84ad-4cf2-8952-f971c7f7d604" />
<img width="1366" height="418" alt="power up v3 2" src="https://github.com/user-attachments/assets/a3e1bfdb-859e-4e58-aad3-6dfd5754c69c" />
<img width="1366" height="418" alt="power up v3 3" src="https://github.com/user-attachments/assets/d0f831d7-de43-4d9b-93b9-abe526156b55" />
so now it was time to optimize the BOM many things were going out of my BOM so I decided to use local store to purchase those components and the smd holder was twice the price of nowmal holder so I got that only I needed to make sure that the dimensions were correct for everything

Time spent - 3 Hr
