// A simple script to enhance interaction
document.addEventListener('DOMContentLoaded', function() {
    const workoutSections = document.querySelectorAll('.workout');
    workoutSections.forEach(function(workout) {
        workout.addEventListener('click', function() {
            alert('Great choice! Keep practicing and you’ll improve!');
        });
    });
});
