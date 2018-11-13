# A production management and supervision system for the printing industry

## What the system aims at solving
The printing industry is being challenged by the increasing price of resources like paper, ink and energy meanwhile 
clients are asking for lower prices. One solution is to optimise 
productivity by reducing as much as possible the resources consumed 
as input while achieving the same amount of output.

## What the system provides
I have implemtented a system to help this industry to deal with this situation. The SGR system provides the opportunity to improve productivity by facilitating decision making. The SGR system :
- Provides real time production indicators to produce the required quantity and avoid wasting resources 
- Tracks production incidents and identifies the weaknesses helping the maintenance team to prioritise their actions 
- Allows all teams to share the same information resulting in strong crosse-team communication and organisation 
- Assists decision makers in refining their strategy and choice of investment by prodviding more than 50 different KPIs

## Technical stack
I have used the .NET stack :
- C#, Entities, Linq
- MSSQL Express
- XAML and the Telerik framework for user interfaces
- Windows Services


## Some examples of features


### Job management before production 

The jobs awaiting entry to production can be easily managed through this interface. For instance, the team in charge of preparing jobs can with a single click change the status of a job to make it available for the production team.

![Screenshot](images/online/manage_jobs_to_run.jpg)

They can also rely on tools such as "duplicate" to avoid filling out similar jobs manually. As a result, even a complicated job can be set in 1 minute.

![Screenshot](images/online/job_details.jpg)

### Monitor the ongoing jobs

The production teams monitor in real-time the ongoing job on their rotary. The system delivers all the indicators they need to produce the required quantity and save resources.

![Screenshot](images/online/real_time_job_supervision_for_rotary_drivers.jpg)

Production managers and all the users who need to can oversee in real-time the ongoing production on all the rotaries at the same time.

![Screenshot](images/online/real_time_job_supervision_for_responsables.jpg)

### Reviewing Ongoing/Completed Jobs

 Production managers can quickly check the status of ongoing/completed jobs.

![Screenshot](images/online/stats_quickview_for_a_job.jpg)

Another view is provided to check the completed jobs following an horizontal time-line

![Screenshot](images/online/unit_job_analysis.jpg)

### Analyse production trends over the time

The decision makers can rely on the provided analysis module to find out more about the production trends over the time by exploring more than 50 KPIs through data tables, figures and dashboard.

![Screenshot](images/online/whole_production_analysis.jpg)






