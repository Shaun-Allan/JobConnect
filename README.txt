####################################################      JOB CONNECT        ########################################################

JobConnect is job seeking platform used by seekers as well as Talent Acqusition Managers of a Company to recruit deserving seekers

PROJECT DESCRIPTION:
    JobConnect gets the details and the constraints of a seeker and shows the recommended jobs for that seeker with the repsective
    recommendedation percentage using machine learning algorithms.
    Similarily Talent Acquisition Team of a Company can entter their details and required constraints and the app shows the recommended
    seekers with their respective recommendedation percentage using machine learning algorithms.
    Also, the seekers can apply for their desired jobs through the platform itself without using any  third party softwares, and the
    Talend Acquistion Team can either reject or apply their appplication.

-----------------------------------------------------------------------------------------------------------------------------------------

INSTALLATION GUIDE:
    First the C files must be compiled byusing the terminal.
    The C files can be compiled using either of the following commands:
        - make
        - gcc main.c seeker.c company.c recommend_jobs.c recommend_seekers.c ScoreCalculation/score.c applications.c validation.c sha256.c -o app

    After intsalling the application to run or exexcute, the application use the following command in the terminal:
        ./app

    NOTE: Check the current directory of the terminal before compilind the C files. Navigate to the appropriate directory where the
          application is stored using the cd command.

-----------------------------------------------------------------------------------------------------------------------------------------

HOW TO USE THE APPLICATION:
    - The application has a register and login setup.
    - So a user, either seeker or talent acquistion manager is expected to create a new account by enterring the required details asked by
      the application.
    - After creating a new account the seeker will be displayed the recommended jobs with the respective recommendation percent.
    - Similary, the talent acquisition manager, the recommended seekers will be displayed with the respective recommendation percent.
    - Later, the user can login to their account using their respective credentials.
    - A seeker can also apply to their desired jobs in a company.
    - The talent acquisition managers will be notified of the application when logged in with their account.
    - The talent acquisition managers can accept or reject the application of the seeker.
    - The seeker will be notified of the application status when he/she logged in with their account.

-----------------------------------------------------------------------------------------------------------------------------------------

************************************************************************************************************************

IMPORTANT NOTE: 
    The user is adviced not to edit or modify any of the files especially the .dat files in the directory.

************************************************************************************************************************

-----------------------------------------------------------------------------------------------------------------------------------------
AUTHORS:
    Shaun Allan. H          3122 22 5001 127
    Saisandeep Sangeetham   3122 22 5001 119
    Shreyamanisha C. Vinay  3122 22 5001 130
------------------------------------------------------------------------------------------------------------------------------------------