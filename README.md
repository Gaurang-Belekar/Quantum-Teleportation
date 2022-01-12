# Quantum-Teleportation

This code simply consist of teleporting information of first qubit (q0) having information |1> to the 3rd qubit (q2) with help of an entagled state q1 entangled to q2.

The Teleportation Protocol suggest us:

1. Creating an EPR (Einstein–Podolsky–Rosen) pair of the destination qubit and the medium through which it could be telported.
2. After entangling, we measure the medium of the pair with respect to the source, whose information is to be transfered.
3. After measuring the Information to be transfered, we then measure the information that has been teleported with help of entanglement.
4. We use Pauli X-Gate and Pauli Z-Gate to measure the destination output. Which gives us the teleported information for any state of superpostion of the entangled medium.

# Input:

<img width="174" alt="Screenshot 2022-01-10 at 11 35 10 AM" src="https://user-images.githubusercontent.com/69144860/148724174-90583b82-874d-4487-9cd7-33746faa2229.png">

Here we have taken input q0 = |1>

# Output:

<img width="495" alt="Screenshot 2022-01-10 at 11 33 44 AM" src="https://user-images.githubusercontent.com/69144860/148724105-52bced07-e93b-4f3b-9a4b-816671c865b4.png">

Now we see thet last qubit displayed in histogram is the q2. Here the q2 is |1> for any possiblity of q0 and q1.

This implies that for the information of q0 is successfully teleported to q2.
We also observe that the very act of bell measurement of q0 wrt q1 as destroyed the information of q0 but is fully restored into q2.
