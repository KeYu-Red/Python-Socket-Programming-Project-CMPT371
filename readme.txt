1. The code in calcClient.py is the same as it in chatClient.py

2. I create a fuction named KeepCalculate in calcServer.py, which is used to put the 
    function recv_from_client into a loop. And if I tape 'q' in the Client, then this 
    thread will jumo out of the loop.

3. I just used and modified recv_from_client function, and not used send_to_client function.

