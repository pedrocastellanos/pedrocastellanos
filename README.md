import SoftwareDeveloper from 'pedrocastellanos';

class Bio extends SoftwareDeveloper {
    name     = 'Pedro Castellanos Alonso';
    stack    = 'Frontend Developer';
    location = 'Cuba';
}

class Skills extends SoftwareDeveloper {
    languages = ['HTML', 'CSS', 'JavaScript'];

    preprocessos = {
        html: 'Pug',
        css: 'Sass/SCSS',
        javascript: {
            typescript: async () => await learning()
        }
    };

    othersTecnologies = {
        versionControl: 'Git',
        softwareHosting: 'GitHub',
        linterns: 'ESLint',
        formaters: 'Prettier',
        tasksRunners: {
            gulp: true,
            webpack = async () => await learn()
        }
    };

    frameworks = 'React';

    node = async () => await learning()
}
