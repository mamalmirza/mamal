<script>
    import AboutMe from "../components/AboutMe.svelte";
    import Item from "../components/Item.svelte";
    import ProjectView from "../components/ProjectView.svelte";

    const experience = [
        {
            title: 'Research Assistant',
            description: 'Dr. Esmaeil Najafi’s Research Group',
            time: 'Sep 2019 - Present ',
            location: 'K. N. Toosi University of Technology'
        },
        {
            title: 'Teaching Assistant',
            description: 'Technical Drawing II',
            time: 'Dec 2016 - Jan 2020',
            location: 'K. N. Toosi University of Technology'
        },
        {
            title: 'Research Assistant',
            description: 'Dr. Mohammad Ravanidi’s Lab',
            time: 'Aug 2019 - May 2020 ',
            location: 'K. N. Toosi University of Technology'
        },
        {
            title: 'Teaching Assistant',
            description: 'Engineering Drawing',
            time: 'Jan 2019 - June 2019 ',
            location: 'K. N. Toosi University of Technology'
        }, 
        {
            title: 'Research Assistant',
            description: 'KN2C Lab',
            time: 'Nov 2016 - Aug 2019 ',
            location: 'K. N. Toosi University of Technology'
        }
        ,
        {
            title: 'Teaching Assistant',
            description: 'Technical Drawing I',
            time: 'Sep 2018 – Jan 2019',
            location: 'K. N. Toosi University of Technology'
        },
    ];

    const honors = [
        {
            title: '3rd Place, RoboCup Asia Pacific',
            description: 'Real Rescue Robots League',
            time: '2018',
            location: 'Iran'
        },
        {
            title: '5th Place, RoboCup',
            description: 'Real Rescue Robots League',
            time: '2017',
            location: 'Japan'
        },
        {
            title: '3rd Place, RoboCup Iran Open',
            description: 'Real Rescue Robots League',
            time: '2018',
            location: 'Iran'
        },
        {
            title: '3rd Place, RoboCup Iran Open',
            description: 'Real Rescue Robots League',
            time: '2017',
            location: 'Iran'
        },
        {
            title: 'Best in Class innovation, RoboCup Iran Open',
            description: 'Real Rescue Robots League',
            time: '2018',
            location: 'Iran'
        },
    ];


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
        }
    ];
</script>

<style>
</style>

<svelte:head>
    <title>Mohmmad Reza Mirzaei</title>
</svelte:head>

<AboutMe/>

<Item itemToShow={experience} title="EXPERIENCE"/>

<ProjectView projectsToShow={projects} showMore='/projects'/>

<Item itemToShow={honors} title="HONORS"/>


