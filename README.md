# motor-check-overflow
A project to check optimal method to switch on a motor based on signals of water level

### Working:
    We will be using simulated waterflow data from other sources and assume a reservoir beneath and a water tank overhead which both contribute to water supply for a facility.
    The waterflow is assumed to be random and based on sources: https://blog.boshart.com/whats-your-home-water-flow-rate-number
    
    We will use genetic algorithms and other algos in order to find the optimal position of sensors such that the total cost of electric operation of motor is minimised and risk of emptying the water tank overhead is reduced.
    
    Waterflow is assumed as input and water consumption as output.
    
    Waterflow-> Reservoir.
    
    Reservoir -> Overhead tank via motor
    
    Overhead tank -> Water consumption.
