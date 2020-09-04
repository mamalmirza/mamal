<script>
    import ProjectView from "../components/ProjectView.svelte";

    const projects = [
        {
            title: 'Camera Dolly',
            description: 'Designing a camera dolly with a hydraulic manipulator',
            time: '2020',
            img: './projectImg/example-project.jpg'
        },
        {
            title: 'Sub-sea wire saw',
            description: 'Designing a sub-sea wire saw for sub-sea pipe maintenance',
            time: '2020',
            img: './projectImg/sub-sea-saw.jpg'
        },
        {
            title: 'Motion Planner of a Mobile Robot in a Partially Observable Environment',
            description: 'Modeling motion planning problem for a mobile robot in an unknown environment',
            time: '2020',
            img: './projectImg/motion.jpg'
        },{
            title: 'Rescue Robot',
            description: 'Designing the chassis of a rescue robot for RoboCup Rescue Competitions',
            time: '2018',
            img: './projectImg/arta.jpg'
        },
        {
            title: 'Smart pill box',
            description: 'Designing a pill box to remind dementia patients to take their pills',
            time: '2018',
            img: './projectImg/pillbox.jpg'
        },{
            title: 'Self stabilizing spoon',
            description: 'Desingining a spoon to control the hand vibration of demantia patients',
            time: '2018',
            img: './projectImg/spoon.jpg'
        },{
            title: 'N-N base detecting handwritten digits',
            description: 'Digital number detection using neural network',
            time: '2019',
            img: './projectImg/digit.jpg'
        } 
    ];
</script>

<ProjectView projectsToShow={projects}></ProjectView>
