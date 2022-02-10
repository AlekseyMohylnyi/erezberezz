<template>
    <div class="clock">
        <div class="clock__title">Time Laps</div>
        <div class="clock__face">
            <h4 class="clock__day">Sunday</h4>
            <h3 class="clock__date">Sep 24, 2020</h3>
            <h2 class="clock__time">08 : 30</h2>
            <h4 class="clock__alarm">
                <div class="clock__alarm-time">9:00</div>
                <div class="clock__alarm-icon">
                    <img src="../assets/images/icons/alarm-icon.svg" alt="alarm">
                </div>
            </h4>
        </div>
    </div>
</template>

<style>
.clock__title {
  font-family: 'Poppins-SemiBold';
  font-size: 1rem;
  color: var(--green);
  text-align: center;  
}

.clock__face {
    border: 5px solid var(--dark);
    margin: 3.75rem;
    padding: 5rem;
    padding-top: 2rem;
    text-align: center;
    border-radius: 50%;
}

.clock__day {
    font-family: 'Poppins-Medium';
    font-size: 1rem;
}
</style>