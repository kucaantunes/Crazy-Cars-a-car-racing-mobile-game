# Crazy-Cars-a-car-racing-mobile-game

![image](https://github.com/user-attachments/assets/54ae6bdd-42ea-4d37-bbb4-130e543f61bb)


![image](https://github.com/user-attachments/assets/5c13a428-da18-44c5-a44e-89e219b2eda0)



https://www.youtube.com/watch?v=HKs0WK-7f4E
 

































ANALYSIS
This Project is based on replicating real events into a computer game that describes the behavior of car AI  and how they interact with the environment.
It was used different types of render and different software for imaging treatment, and for the processing and sequencing of different units.
It reveals the simulation of a car race.
















Choose theme / application
This theme was chosen due to the technical requirements of making a game it uses an engine in this case it was unity and android studio, the application runs on Android.
During the development of this project several sprints were performed where it was defined the objectives of the project.
Nowadays the tendency of playing computer games on mobile is high there are several cases of success like flappy birds, angry birds, minecraft, and the games from electronic arts, gameloft and warner bros, among many other cases.
Due to the timeline restriction, the project only has 3 type of cars and 3 types of tracks, one of the tracks is a city and occupies too much space and processing capacity although it is working fine on the windows x86 and on the web versions, it is not working on the mobile used for testing.
The city level should run ok on higher capacity mobiles, although one of the objectives of the project is that the application works fine for different types of mobile so the city level was removed from the mobile version.
When pressing some buttons the processor takes some time to execute for example loading levels, because the levels have lots of information that delay the execution, although this delay time will not occur in mobiles with higher processor capacity.
The game uses new cars like a Mercedes, and tries to simulate a racing car game.
Car race games have been developing, and it is something that is easy to sell.










Environment Adjustment
The basis is concerning a car race of several types of cars and several races.
The available cars are:
 
The second car:





The third car:












The tracks are:
 
The second track:





The third track:
 






The scope of this project is based on the development of a game that simulates a car race where the gear being used and the speed are displayed. It has opponent cars and several tracks. Users are able to change the camera there is the upper view and the inside car options. There are 3 tracks available although one of the tracks is a city and stays on loading stage on the test mobile, although it works fine on the standalone and the web versions.
This project simulates the behavior of racing cars and has and interface with end user via mobile, the player can drive the car in his preferable perspective from the set offered.
It is based on visual programming and the main objective is to offer fun for the person that is going to use it.

https://youtu.be/aXAlczPhU18

 




Justify its need

Although it is a game, it can find a necessity in areas like education, simulating a car drive scenario. Many games reached high levels of success on the mobile industry. Many companies invest and profit high monetary levels.
It can be profitable, and it is easy to implement, any use who has previously installed an application on his mobile, should not have difficulties in installing and implementing the crazy cars game.
It is better than some other car simulators. It is portable, can be played on Windows, web and mobile, and does not require a very powerful phone processor because we have removed lots of contents.
It has several functionalities, like the option to steer when moving the mobile to turn or pressing the buttons to turn. It has a brake system, it has the functionality of returning to the main menu and also it offers 3 camera vies one from behind the car, an upper view camera and one inside the car.
It was a theme song done with an acoustic guitar and recorded in Lisbon.
It has the functionalities of choosing cars and choosing tracks.
Might have many interested users.
Tests were made and many people spoke well about the game that the graphic quality was high, and that looked fine.
It is easy to play, although at the beginning some users might find difficulties because the accelerator and the turn buttons cannot stay pressed for too long.















The application has the following functionalities: 
 	Car Artificial intelligence
 	Starting Menu
 	Car selection
 	Track selection
 	Several cameras and several points of view
 	It has the accelerometer functionality, the car turns when the phone is turned
 	Buttons to speed, brake, turn, restart level, go back to main menu and to change camera

 





User Manual


First download the crazycars.apk file to your phone. The file can be found at:
https://iscteiul365-my.sharepoint.com/personal/cfpcm_iscte-iul_pt1/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fcfpcm_iscte-iul_pt1%2FDocuments%2FDesenvolvimento%20de%20Aplica%C3%A7%C3%B5es%20para%20Ambientes%20M%C3%B3veis
After downloading the file to your phone, click on it, it should start the install process, to find the file it can be used one of the several file managers available on the google play store. After the installation process is done it will appear the option if you wish to open the application or not. After the installation the application will appear on the applications menu, and to play it is only needed to click on it, the icon should look like this: 


After starting the application the following menu should appear.














By clicking on start it will start the game, by clicking on options it will appear the game options, by clicking on cars you will be able to see the available cars, by clicking on tracks you should be able to view the available tracks, by clicking quit it will terminate the application.
When clicking start you will see the following menu:
 
In this menu choose the car you wish to play with from the 3 available cars. The firs is a Mercedes the second an Austin Martin. 
After choosing the car you wish, you should be able to see the existing tracks:











On both these 2 menus, the arrow on the upper right corner will take you back to the main menu in both scenarios. On the track menu click the track that you wish to play there are 3 tracks available: desert, city and night mountains.



Requirements Identification


 	The system should allow an interface for user to play game, define variables and parameters
 	The system should register the number of vehicles per lane
 	The system should register the level of gas consumption
 	The system should allow to control the car and move around the scenario
 	The system should register the speed and gear being used
 	The system should allow to monitor and zoom view for the main car
 	The system should display different cars doing different trajectories  
 	The system should allow an interface for user to play game, define variables and parameters
 	The system should have an option to distinguish when it is mobile or when it is to be used as standalone or web
 	The system should allow to choose from a number of cars and tracks.
 	The system should simulate realistic values
 	The system should register the speed of the vehicles
 	The system should allow to register and define acceleration and deceleration
 	The system should follow a the main car 
 	The system should have more than 1 lane for each track.
 	The system should simulate the performance of a real car
 	The system should display the logo 
 	The system should have buttons to allow the car to move left, right, down or up 
 	The system should allow the car to rotate according with the turn of the mobile
 	The system should show the speed 
 	The system should record data for the number of cars 
 	The system should have a game based interface
 	The system should have 3 menus at least: 1 general, 1 for cars and 1 for tracks

Requirements Identification – Use cases

We should explain the interaction between the user and the system showing the functionalities and the systems he is interacting with:
 
On the image above we can see the functionalities and also getting data from a file that can be generated by another system offering the possibility of creating an API.
The main activities are playing games, defining variables, defining parameters, checking graphics, calculating statistical data among other factors.
 







Select and justify the development technology used
This project is based on developing a car race simulator, the technology used was Unity due to time restrictions. Other projects were made in parallel using other engines like Unral Engine and Cryengine, Cryengine has the limitation that can not be exported to mobile or web.
Many of the mobile games available on google play are based in unreal engine, but this project was made in order to look the most realistic as possible, strategy followed by many of the bigger companies in the game development area like Ubisoft and Electronic Arts. 
The technology used was 3DS max fir modelling and rigging, the major part of the game was made in unity, it was also used OpenShot and other movie editors. 
We have decided to follow C# instead of Java, and the project is not open source based, although developers vary on the opinion of which technology to be used, we have followed a strategy not based in open source technologies.
It was also used JavaScript. This technology used allows to export to iPhone, web, mac, windows, playstation, etc…
Due to lack of funds we were not able to obtain a iPhone for testing, so it was made for Android.
Due to high graphic quality and processing effort, the game works fine on mobiles above 2.0 Ghz and above 6 GB.
Tested on Samsung Galaxy 9 the game works fine, on the galaxy S6 edge plus, there is some processor delay on reading the user`s input.
The tested phone which works fine was:
10nm 64-bit Octa-Core Processor *2.8GHz + 1.7GHz (Maximum Clock Speed, Performance Core + Efficiency Core)
10nm 64-bit Octa-Core Processor *2.7GHz + 1.7GHz (Maximum Clock Speed, Performance Core + Efficiency Core)
Galaxy S9+
6GB RAM
64GB

The Unity version used was the 2019 and the latest build. It was upgraded during project development and allowed to place the level city which the team faced issues on exprting with previous versions of unity.


Main Menu:
 
Car Selection Menu:
 
Track Selection Menu:
 

Desert Track:
 

City Track:
 
Night Mountains Track:
 


Story Board - Menu System:


















Game start:								Pass the cars:






                  Finish Dsiplay:                                                                          Reach the transparent Circle


System`s Functionalities


The system has a menu interface with a video and music. 2 Different musics were selected for this application one during the menu and another during in game. The system should have the functionalities of turning accelerating, braking and revers.
The functionality when selected of turning when the mobile phone turns. The option of activating only when the button is being pressed and not on one click for turning, breaking and accelerating. When pressing the brake button and reaches the speed of 0 KM per Hour the camera flips and the car starts moving backwards.
It should have the functionalities of choosing cars and choosing tracks.
It has 3 scenarios, desert, city and night, and 3 optional cars.
The opponent cars should have an intelligent system of following points on the scenario that are not visible, it has AI path, motion and the cars have different behaviors.
It should have the functionality of changing view, there are currently 3, one that the camera is behind the car, one of upper view and a third one where the camera is inside the car.
It has the functionality of restarting the level every time the correspondent button is clivked.
The functionality of returning to the main menu.
The functionality of showing a congratulations panel based on trigger when the player car reaches the final check point.
Should be user friendly.









System`s Limitations

This system in order to be executed it is recommended a minimum speed of 2.0 Ghz, it has been tested on Windows 8.1 and windows 10. 
It does not require the installation of extra libraries on the mobile.
The city level because it has a city requires a mobile with a high processor capacity in order to be played, the mobile used for testing was not able to run it due to processor limit.
Does not require a web browser.
It has a limit of the number of cars and tracks.
Because it is for mobile there are some graphical and size limitations.
It requires the use of a phone with android.
The tracks have boundaries.
When the car crashes it does not damage the vehicle.
The car AI is not related with the player performance.
Requires android studio on the dev computer.
It is running for some versions of Android.












Parameters and Entities
It has several parameters like speed, braking, moving backwards, turning, isMobile, trackID, CarID among others, there are at least 4 AI entities, the AI cars only move around the AI area defined on the scenario, the AI for each track has different wave points, in general for each track were used around 40 AI wave points.
The player entity has several scripts for controlling and interacting with the camera and the mobile interface.
There was set several parameters like maximum speed, maximum gear, for quaternions (when turning) and the camera changes position according to speed and player position.





















Expected Results


The expected results are to simulate a car race close to the reality. for different time frames the AI cars have the information of which is the best lane or the best process to fulfill in order to provide an efficient passage till the final checkpoint. The track has several AI wavepoints. Variables like speed acceleration and number of cars will be taken in account.
The system will measure the number of cars and will also mention how AI cars should proceed, there will be correlations between variables and statistics values for different distributions that will be generated for the different scenarios.

It will measure the driving performance for each lane and will look for the optimization of time. It will present several displays and graphs for the different agents


Some of the several classes used.
                                                         

Class for controlling the car and interface buttons.


using System;
using UnityEngine;

namespace UnityStandardAssets.Vehicles.Car
{
    internal enum CarDriveType
    {
        FrontWheelDrive,
        RearWheelDrive,
        FourWheelDrive
    }

    internal enum SpeedType
    {
        MPH,
        KPH
    }

    public class CarController : MonoBehaviour
    {
        [SerializeField] private CarDriveType m_CarDriveType = CarDriveType.FourWheelDrive;
        [SerializeField] private WheelCollider[] m_WheelColliders = new WheelCollider[4];
        [SerializeField] private GameObject[] m_WheelMeshes = new GameObject[4];
        [SerializeField] private WheelEffects[] m_WheelEffects = new WheelEffects[4];
        [SerializeField] private Vector3 m_CentreOfMassOffset;
        [SerializeField] private float m_MaximumSteerAngle;
        [Range(0, 1)] [SerializeField] private float m_SteerHelper; // 0 is raw physics , 1 the car will grip in the direction it is facing
        [Range(0, 1)] [SerializeField] private float m_TractionControl; // 0 is no traction control, 1 is full interference
        [SerializeField] private float m_FullTorqueOverAllWheels;
        [SerializeField] private float m_ReverseTorque;
        [SerializeField] private float m_MaxHandbrakeTorque;
        [SerializeField] private float m_Downforce = 100f;
        [SerializeField] private SpeedType m_SpeedType;
        [SerializeField] private float m_Topspeed = 200;
        [SerializeField] private static int NoOfGears = 5;
        [SerializeField] private float m_RevRangeBoundary = 1f;
        [SerializeField] private float m_SlipLimit;
        [SerializeField] private float m_BrakeTorque;

        private Quaternion[] m_WheelMeshLocalRotations;
        private Vector3 m_Prevpos, m_Pos;
        private float m_SteerAngle;
        private int m_GearNum;
        private float m_GearFactor;
        private float m_OldRotation;
        private float m_CurrentTorque;
        private Rigidbody m_Rigidbody;
        private const float k_ReversingThreshold = 0.01f;

        public bool Skidding { get; private set; }
        public float BrakeInput { get; private set; }
        public float CurrentSteerAngle{ get { return m_SteerAngle; }}
        public float CurrentSpeed{ get { return m_Rigidbody.velocity.magnitude*2.23693629f; }}
        public float MaxSpeed{get { return m_Topspeed; }}
        public float Revs { get; private set; }
        public float AccelInput { get; private set; }

        // Use this for initialization
        private void Start()
        {
            m_WheelMeshLocalRotations = new Quaternion[4];
            for (int i = 0; i < 4; i++)
            {
                m_WheelMeshLocalRotations[i] = m_WheelMeshes[i].transform.localRotation;
            }
            m_WheelColliders[0].attachedRigidbody.centerOfMass = m_CentreOfMassOffset;

            m_MaxHandbrakeTorque = float.MaxValue;

            m_Rigidbody = GetComponent<Rigidbody>();
            m_CurrentTorque = m_FullTorqueOverAllWheels - (m_TractionControl*m_FullTorqueOverAllWheels);
        }


        private void GearChanging()
        {
            float f = Mathf.Abs(CurrentSpeed/MaxSpeed);
            float upgearlimit = (1/(float) NoOfGears)*(m_GearNum + 1);
            float downgearlimit = (1/(float) NoOfGears)*m_GearNum;

            if (m_GearNum > 0 && f < downgearlimit)
            {
                m_GearNum--;
            }

            if (f > upgearlimit && (m_GearNum < (NoOfGears - 1)))
            {
                m_GearNum++;
            }
        }


        // simple function to add a curved bias towards 1 for a value in the 0-1 range
        private static float CurveFactor(float factor)
        {
            return 1 - (1 - factor)*(1 - factor);
        }


        // unclamped version of Lerp, to allow value to exceed the from-to range
        private static float ULerp(float from, float to, float value)
        {
            return (1.0f - value)*from + value*to;
        }


        private void CalculateGearFactor()
        {
            float f = (1/(float) NoOfGears);
            // gear factor is a normalised representation of the current speed within the current gear's range of speeds.
            // We smooth towards the 'target' gear factor, so that revs don't instantly snap up or down when changing gear.
            var targetGearFactor = Mathf.InverseLerp(f*m_GearNum, f*(m_GearNum + 1), Mathf.Abs(CurrentSpeed/MaxSpeed));
            m_GearFactor = Mathf.Lerp(m_GearFactor, targetGearFactor, Time.deltaTime*5f);
        }


        private void CalculateRevs()
        {
            // calculate engine revs (for display / sound)
            // (this is done in retrospect - revs are not used in force/power calculations)
            CalculateGearFactor();
            var gearNumFactor = m_GearNum/(float) NoOfGears;
            var revsRangeMin = ULerp(0f, m_RevRangeBoundary, CurveFactor(gearNumFactor));
            var revsRangeMax = ULerp(m_RevRangeBoundary, 1f, gearNumFactor);
            Revs = ULerp(revsRangeMin, revsRangeMax, m_GearFactor);
        }


        public void Move(float steering, float accel, float footbrake, float handbrake)
        {
            for (int i = 0; i < 4; i++)
            {
                Quaternion quat;
                Vector3 position;
                m_WheelColliders[i].GetWorldPose(out position, out quat);
                m_WheelMeshes[i].transform.position = position;
                m_WheelMeshes[i].transform.rotation = quat;
            }

            //clamp input values
            steering = Mathf.Clamp(steering, -1, 1);
            AccelInput = accel = Mathf.Clamp(accel, 0, 1);
            BrakeInput = footbrake = -1*Mathf.Clamp(footbrake, -1, 0);
            handbrake = Mathf.Clamp(handbrake, 0, 1);

            //Set the steer on the front wheels.
            //Assuming that wheels 0 and 1 are the front wheels.
            m_SteerAngle = steering*m_MaximumSteerAngle;
            m_WheelColliders[0].steerAngle = m_SteerAngle;
            m_WheelColliders[1].steerAngle = m_SteerAngle;

            SteerHelper();
            ApplyDrive(accel, footbrake);
            CapSpeed();

            //Set the handbrake.
            //Assuming that wheels 2 and 3 are the rear wheels.
            if (handbrake > 0f)
            {
                var hbTorque = handbrake*m_MaxHandbrakeTorque;
                m_WheelColliders[2].brakeTorque = hbTorque;
                m_WheelColliders[3].brakeTorque = hbTorque;
            }


            CalculateRevs();
            GearChanging();

            AddDownForce();
            CheckForWheelSpin();
            TractionControl();
        }


        private void CapSpeed()
        {
            float speed = m_Rigidbody.velocity.magnitude;
            switch (m_SpeedType)
            {
                case SpeedType.MPH:

                    speed *= 2.23693629f;
                    if (speed > m_Topspeed)
                        m_Rigidbody.velocity = (m_Topspeed/2.23693629f) * m_Rigidbody.velocity.normalized;
                    break;

                case SpeedType.KPH:
                    speed *= 3.6f;
                    if (speed > m_Topspeed)
                        m_Rigidbody.velocity = (m_Topspeed/3.6f) * m_Rigidbody.velocity.normalized;
                    break;
            }
        }


        private void ApplyDrive(float accel, float footbrake)
        {

            float thrustTorque;
            switch (m_CarDriveType)
            {
                case CarDriveType.FourWheelDrive:
                    thrustTorque = accel * (m_CurrentTorque / 4f);
                    for (int i = 0; i < 4; i++)
                    {
                        m_WheelColliders[i].motorTorque = thrustTorque;
                    }
                    break;

                case CarDriveType.FrontWheelDrive:
                    thrustTorque = accel * (m_CurrentTorque / 2f);
                    m_WheelColliders[0].motorTorque = m_WheelColliders[1].motorTorque = thrustTorque;
                    break;

                case CarDriveType.RearWheelDrive:
                    thrustTorque = accel * (m_CurrentTorque / 2f);
                    m_WheelColliders[2].motorTorque = m_WheelColliders[3].motorTorque = thrustTorque;
                    break;

            }

            for (int i = 0; i < 4; i++)
            {
                if (CurrentSpeed > 5 && Vector3.Angle(transform.forward, m_Rigidbody.velocity) < 50f)
                {
                    m_WheelColliders[i].brakeTorque = m_BrakeTorque*footbrake;
                }
                else if (footbrake > 0)
                {
                    m_WheelColliders[i].brakeTorque = 0f;
                    m_WheelColliders[i].motorTorque = -m_ReverseTorque*footbrake;
                }
            }
        }


        private void SteerHelper()
        {
            for (int i = 0; i < 4; i++)
            {
                WheelHit wheelhit;
                m_WheelColliders[i].GetGroundHit(out wheelhit);
                if (wheelhit.normal == Vector3.zero)
                    return; // wheels arent on the ground so dont realign the rigidbody velocity
            }

            // this if is needed to avoid gimbal lock problems that will make the car suddenly shift direction
            if (Mathf.Abs(m_OldRotation - transform.eulerAngles.y) < 10f)
            {
                var turnadjust = (transform.eulerAngles.y - m_OldRotation) * m_SteerHelper;
                Quaternion velRotation = Quaternion.AngleAxis(turnadjust, Vector3.up);
                m_Rigidbody.velocity = velRotation * m_Rigidbody.velocity;
            }
            m_OldRotation = transform.eulerAngles.y;
        }


        // this is used to add more grip in relation to speed
        private void AddDownForce()
        {
            m_WheelColliders[0].attachedRigidbody.AddForce(-transform.up*m_Downforce*
                                                         m_WheelColliders[0].attachedRigidbody.velocity.magnitude);
        }


        // checks if the wheels are spinning and is so does three things
        // 1) emits particles
        // 2) plays tiure skidding sounds
        // 3) leaves skidmarks on the ground
        // these effects are controlled through the WheelEffects class
        private void CheckForWheelSpin()
        {
            // loop through all wheels
            for (int i = 0; i < 4; i++)
            {
                WheelHit wheelHit;
                m_WheelColliders[i].GetGroundHit(out wheelHit);

                // is the tire slipping above the given threshhold
                if (Mathf.Abs(wheelHit.forwardSlip) >= m_SlipLimit || Mathf.Abs(wheelHit.sidewaysSlip) >= m_SlipLimit)
                {
                    m_WheelEffects[i].EmitTyreSmoke();

                    // avoiding all four tires screeching at the same time
                    // if they do it can lead to some strange audio artefacts
                    if (!AnySkidSoundPlaying())
                    {
                        m_WheelEffects[i].PlayAudio();
                    }
                    continue;
                }

                // if it wasnt slipping stop all the audio
                if (m_WheelEffects[i].PlayingAudio)
                {
                    m_WheelEffects[i].StopAudio();
                }
                // end the trail generation
                m_WheelEffects[i].EndSkidTrail();
            }
        }

        // crude traction control that reduces the power to wheel if the car is wheel spinning too much
        private void TractionControl()
        {
            WheelHit wheelHit;
            switch (m_CarDriveType)
            {
                case CarDriveType.FourWheelDrive:
                    // loop through all wheels
                    for (int i = 0; i < 4; i++)
                    {
                        m_WheelColliders[i].GetGroundHit(out wheelHit);

                        AdjustTorque(wheelHit.forwardSlip);
                    }
                    break;

                case CarDriveType.RearWheelDrive:
                    m_WheelColliders[2].GetGroundHit(out wheelHit);
                    AdjustTorque(wheelHit.forwardSlip);

                    m_WheelColliders[3].GetGroundHit(out wheelHit);
                    AdjustTorque(wheelHit.forwardSlip);
                    break;

                case CarDriveType.FrontWheelDrive:
                    m_WheelColliders[0].GetGroundHit(out wheelHit);
                    AdjustTorque(wheelHit.forwardSlip);

                    m_WheelColliders[1].GetGroundHit(out wheelHit);
                    AdjustTorque(wheelHit.forwardSlip);
                    break;
            }
        }


        private void AdjustTorque(float forwardSlip)
        {
            if (forwardSlip >= m_SlipLimit && m_CurrentTorque >= 0)
            {
                m_CurrentTorque -= 10 * m_TractionControl;
            }
            else
            {
                m_CurrentTorque += 10 * m_TractionControl;
                if (m_CurrentTorque > m_FullTorqueOverAllWheels)
                {
                    m_CurrentTorque = m_FullTorqueOverAllWheels;
                }
            }
        }


        private bool AnySkidSoundPlaying()
        {
            for (int i = 0; i < 4; i++)
            {
                if (m_WheelEffects[i].PlayingAudio)
                {
                    return true;
                }
            }
            return false;
        }
    }
}



Define AI acceleration, breaking, etc…


using System;
using UnityEngine;
using Random = UnityEngine.Random;

namespace UnityStandardAssets.Vehicles.Car
{
    [RequireComponent(typeof (CarController))]
    public class CarAIControl : MonoBehaviour
    {
        public enum BrakeCondition
        {
            NeverBrake,                 // the car simply accelerates at full throttle all the time.
            TargetDirectionDifference,  // the car will brake according to the upcoming change in direction of the target. Useful for route-based AI, slowing for corners.
            TargetDistance,             // the car will brake as it approaches its target, regardless of the target's direction. Useful if you want the car to
                                        // head for a stationary target and come to rest when it arrives there.
        }

        // This script provides input to the car controller in the same way that the user control script does.
        // As such, it is really 'driving' the car, with no special physics or animation tricks to make the car behave properly.

        // "wandering" is used to give the cars a more human, less robotic feel. They can waver slightly
        // in speed and direction while driving towards their target.

        [SerializeField] [Range(0, 1)] private float m_CautiousSpeedFactor = 0.05f;               // percentage of max speed to use when being maximally cautious
        [SerializeField] [Range(0, 180)] private float m_CautiousMaxAngle = 50f;                  // angle of approaching corner to treat as warranting maximum caution
        [SerializeField] private float m_CautiousMaxDistance = 100f;                              // distance at which distance-based cautiousness begins
        [SerializeField] private float m_CautiousAngularVelocityFactor = 30f;                     // how cautious the AI should be when considering its own current angular velocity (i.e. easing off acceleration if spinning!)
        [SerializeField] private float m_SteerSensitivity = 0.05f;                                // how sensitively the AI uses steering input to turn to the desired direction
        [SerializeField] private float m_AccelSensitivity = 0.04f;                                // How sensitively the AI uses the accelerator to reach the current desired speed
        [SerializeField] private float m_BrakeSensitivity = 1f;                                   // How sensitively the AI uses the brake to reach the current desired speed
        [SerializeField] private float m_LateralWanderDistance = 3f;                              // how far the car will wander laterally towards its target
        [SerializeField] private float m_LateralWanderSpeed = 0.1f;                               // how fast the lateral wandering will fluctuate
        [SerializeField] [Range(0, 1)] private float m_AccelWanderAmount = 0.1f;                  // how much the cars acceleration will wander
        [SerializeField] private float m_AccelWanderSpeed = 0.1f;                                 // how fast the cars acceleration wandering will fluctuate
        [SerializeField] private BrakeCondition m_BrakeCondition = BrakeCondition.TargetDistance; // what should the AI consider when accelerating/braking?
        [SerializeField] private bool m_Driving;                                                  // whether the AI is currently actively driving or stopped.
        [SerializeField] private Transform m_Target;                                              // 'target' the target object to aim for.
        [SerializeField] private bool m_StopWhenTargetReached;                                    // should we stop driving when we reach the target?
        [SerializeField] private float m_ReachTargetThreshold = 2;                                // proximity to target to consider we 'reached' it, and stop driving.

        private float m_RandomPerlin;             // A random value for the car to base its wander on (so that AI cars don't all wander in the same pattern)
        private CarController m_CarController;    // Reference to actual car controller we are controlling
        private float m_AvoidOtherCarTime;        // time until which to avoid the car we recently collided with
        private float m_AvoidOtherCarSlowdown;    // how much to slow down due to colliding with another car, whilst avoiding
        private float m_AvoidPathOffset;          // direction (-1 or 1) in which to offset path to avoid other car, whilst avoiding
        private Rigidbody m_Rigidbody;


        private void Awake()
        {
            // get the car controller reference
            m_CarController = GetComponent<CarController>();

            // give the random perlin a random value
            m_RandomPerlin = Random.value*100;

            m_Rigidbody = GetComponent<Rigidbody>();
        }


        private void FixedUpdate()
        {
            if (m_Target == null || !m_Driving)
            {
                // Car should not be moving,
                // use handbrake to stop
                m_CarController.Move(0, 0, -1f, 1f);
            }
            else
            {
                Vector3 fwd = transform.forward;
                if (m_Rigidbody.velocity.magnitude > m_CarController.MaxSpeed*0.1f)
                {
                    fwd = m_Rigidbody.velocity;
                }

                float desiredSpeed = m_CarController.MaxSpeed;

                // now it's time to decide if we should be slowing down...
                switch (m_BrakeCondition)
                {
                    case BrakeCondition.TargetDirectionDifference:
                        {
                            // the car will brake according to the upcoming change in direction of the target. Useful for route-based AI, slowing for corners.

                            // check out the angle of our target compared to the current direction of the car
                            float approachingCornerAngle = Vector3.Angle(m_Target.forward, fwd);

                            // also consider the current amount we're turning, multiplied up and then compared in the same way as an upcoming corner angle
                            float spinningAngle = m_Rigidbody.angularVelocity.magnitude*m_CautiousAngularVelocityFactor;

                            // if it's different to our current angle, we need to be cautious (i.e. slow down) a certain amount
                            float cautiousnessRequired = Mathf.InverseLerp(0, m_CautiousMaxAngle,
                                                                           Mathf.Max(spinningAngle,
                                                                                     approachingCornerAngle));
                            desiredSpeed = Mathf.Lerp(m_CarController.MaxSpeed, m_CarController.MaxSpeed*m_CautiousSpeedFactor,
                                                      cautiousnessRequired);
                            break;
                        }

                    case BrakeCondition.TargetDistance:
                        {
                            // the car will brake as it approaches its target, regardless of the target's direction. Useful if you want the car to
                            // head for a stationary target and come to rest when it arrives there.

                            // check out the distance to target
                            Vector3 delta = m_Target.position - transform.position;
                            float distanceCautiousFactor = Mathf.InverseLerp(m_CautiousMaxDistance, 0, delta.magnitude);

                            // also consider the current amount we're turning, multiplied up and then compared in the same way as an upcoming corner angle
                            float spinningAngle = m_Rigidbody.angularVelocity.magnitude*m_CautiousAngularVelocityFactor;

                            // if it's different to our current angle, we need to be cautious (i.e. slow down) a certain amount
                            float cautiousnessRequired = Mathf.Max(
                                Mathf.InverseLerp(0, m_CautiousMaxAngle, spinningAngle), distanceCautiousFactor);
                            desiredSpeed = Mathf.Lerp(m_CarController.MaxSpeed, m_CarController.MaxSpeed*m_CautiousSpeedFactor,
                                                      cautiousnessRequired);
                            break;
                        }

                    case BrakeCondition.NeverBrake:
                        break;
                }

                // Evasive action due to collision with other cars:

                // our target position starts off as the 'real' target position
                Vector3 offsetTargetPos = m_Target.position;

                // if are we currently taking evasive action to prevent being stuck against another car:
                if (Time.time < m_AvoidOtherCarTime)
                {
                    // slow down if necessary (if we were behind the other car when collision occured)
                    desiredSpeed *= m_AvoidOtherCarSlowdown;

                    // and veer towards the side of our path-to-target that is away from the other car
                    offsetTargetPos += m_Target.right*m_AvoidPathOffset;
                }
                else
                {
                    // no need for evasive action, we can just wander across the path-to-target in a random way,
                    // which can help prevent AI from seeming too uniform and robotic in their driving
                    offsetTargetPos += m_Target.right*
                                       (Mathf.PerlinNoise(Time.time*m_LateralWanderSpeed, m_RandomPerlin)*2 - 1)*
                                       m_LateralWanderDistance;
                }

                // use different sensitivity depending on whether accelerating or braking:
                float accelBrakeSensitivity = (desiredSpeed < m_CarController.CurrentSpeed)
                                                  ? m_BrakeSensitivity
                                                  : m_AccelSensitivity;

                // decide the actual amount of accel/brake input to achieve desired speed.
                float accel = Mathf.Clamp((desiredSpeed - m_CarController.CurrentSpeed)*accelBrakeSensitivity, -1, 1);

                // add acceleration 'wander', which also prevents AI from seeming too uniform and robotic in their driving
                // i.e. increasing the accel wander amount can introduce jostling and bumps between AI cars in a race
                accel *= (1 - m_AccelWanderAmount) +
                         (Mathf.PerlinNoise(Time.time*m_AccelWanderSpeed, m_RandomPerlin)*m_AccelWanderAmount);

                // calculate the local-relative position of the target, to steer towards
                Vector3 localTarget = transform.InverseTransformPoint(offsetTargetPos);

                // work out the local angle towards the target
                float targetAngle = Mathf.Atan2(localTarget.x, localTarget.z)*Mathf.Rad2Deg;

                // get the amount of steering needed to aim the car towards the target
                float steer = Mathf.Clamp(targetAngle*m_SteerSensitivity, -1, 1)*Mathf.Sign(m_CarController.CurrentSpeed);

                // feed input to the car controller.
                m_CarController.Move(steer, accel, accel, 0f);

                // if appropriate, stop driving when we're close enough to the target.
                if (m_StopWhenTargetReached && localTarget.magnitude < m_ReachTargetThreshold)
                {
                    m_Driving = false;
                }
            }
        }


        private void OnCollisionStay(Collision col)
        {
            // detect collision against other cars, so that we can take evasive action
            if (col.rigidbody != null)
            {
                var otherAI = col.rigidbody.GetComponent<CarAIControl>();
                if (otherAI != null)
                {
                    // we'll take evasive action for 1 second
                    m_AvoidOtherCarTime = Time.time + 1;

                    // but who's in front?...
                    if (Vector3.Angle(transform.forward, otherAI.transform.position - transform.position) < 90)
                    {
                        // the other ai is in front, so it is only good manners that we ought to brake...
                        m_AvoidOtherCarSlowdown = 0.5f;
                    }
                    else
                    {
                        // we're in front! ain't slowing down for anybody...
                        m_AvoidOtherCarSlowdown = 1;
                    }

                    // both cars should take evasive action by driving along an offset from the path centre,
                    // away from the other car
                    var otherCarLocalDelta = transform.InverseTransformPoint(otherAI.transform.position);
                    float otherCarAngle = Mathf.Atan2(otherCarLocalDelta.x, otherCarLocalDelta.z);
                    m_AvoidPathOffset = m_LateralWanderDistance*-Mathf.Sign(otherCarAngle);
                }
            }
        }


        public void SetTarget(Transform target)
        {
            m_Target = target;
            m_Driving = true;
        }
    }
}



//2016 Spyblood Productions
//Use for non-commerical games only. do not sell comercially
//without permission first

using UnityEngine;
using System.Collections;



public enum DriveType
{
	RWD,
	FWD,
	AWD
};
[System.Serializable]
public class WC
{
	public WheelCollider wheelFL;
	public WheelCollider wheelFR;
	public WheelCollider wheelRL;
	public WheelCollider wheelRR;
}
[System.Serializable]
public class WT
{
	public Transform wheelFL;
	public Transform wheelFR;
	public Transform wheelRL;
	public Transform wheelRR;
}
[RequireComponent(typeof(AudioSource))]//needed audiosource
[RequireComponent(typeof(Rigidbody))]//needed Rigid body
public class CarControlCS : MonoBehaviour {

	public WC wheels;
	public WT tires;
	public WheelCollider[] extraWheels;
	public Transform[] extraWheelObjects;
	public DriveType DriveTrain = DriveType.RWD;
	public Vector3 centerOfGravity;//car's center of mass offset
	public GUITexture gasPedal;
	public GUITexture brakePedal;
	public GUITexture leftPedal;
	public GUITexture rightPedal;
    public GUITexture buttonA;
    public GUITexture speed;
    public float maxTorque = 1000f;//car's acceleration value
	public float maxReverseSpeed = 50f;//top speed for the reverse gear
	public float handBrakeTorque = 500f;//hand brake value
	public float maxSteer = 25f;//max steer angle
	public bool mobileInput = false;//do you want this to be a mobile game?
	public float[] GearRatio;//determines how many gears the car has, and at what speed the car shifts to the appropriate gear
	private int throttleInput;//read only
	private int steerInput;//read only
	private bool reversing;//read only
	private float currentSpeed;//read only
	public float maxSpeed = 150f;//how fast the vehicle can go
	private int gear;//current gear
	Vector3 localCurrentSpeed;
    public float x = Input.acceleration.x;
    private Vector3 dir;


    // Use this for initialization
    void Start () {
        throttleInput = 1;
        //find all the GUITextures from the scene and assign them
        gasPedal = GameObject.Find("GasPedal").GetComponent<GUITexture>();
		brakePedal = GameObject.Find("BrakePedal").GetComponent<GUITexture>();
		leftPedal = GameObject.Find("LeftPedal").GetComponent<GUITexture>();
		rightPedal = GameObject.Find("RightPedal").GetComponent<GUITexture>();
        buttonA = GameObject.Find("ButtonA").GetComponent<GUITexture>();
        speed = GameObject.Find("Speed").GetComponent<GUITexture>();
        //Alter the center of mass for stability on your car
        GetComponent<Rigidbody>().centerOfMass = centerOfGravity;
	}
	
	// Update is called once per frame
	void FixedUpdate () {

		if (GetComponent<Rigidbody>().centerOfMass != centerOfGravity)
		GetComponent<Rigidbody>().centerOfMass = centerOfGravity;
		
		AllignWheels ();
		GUIButtonControl();
		DriveMobile ();
		Drive ();
		EngineAudio ();

		currentSpeed = GetComponent<Rigidbody>().velocity.magnitude * 2.23693629f;//convert currentspeed into MPH

		localCurrentSpeed = transform.InverseTransformDirection (GetComponent<Rigidbody> ().velocity);

		//if (currentSpeed > maxSpeed || (localCurrentSpeed.z*2.23693629f) < -maxReverseSpeed){

	}

	void AllignWheels()
	{
		//allign the wheel objs to their colliders

			Quaternion quat;
			Vector3 pos;
			wheels.wheelFL.GetWorldPose(out pos,out quat);
			tires.wheelFL.position = pos;
			tires.wheelFL.rotation = quat;

		wheels.wheelFR.GetWorldPose(out pos,out quat);
		tires.wheelFR.position = pos;
		tires.wheelFR.rotation = quat;

		wheels.wheelRL.GetWorldPose(out pos,out quat);
		tires.wheelRL.position = pos;
		tires.wheelRL.rotation = quat;

		wheels.wheelRR.GetWorldPose(out pos,out quat);
		tires.wheelRR.position = pos;
		tires.wheelRR.rotation = quat;

		for (int i = 0; i < extraWheels.Length; i++)
		{

			for (int k = 0; k < extraWheelObjects.Length; k++) {
			
				Quaternion quater;
				Vector3 vec3;

				extraWheels [i].GetWorldPose (out vec3, out quater);
				extraWheelObjects [k].position = vec3;
				extraWheelObjects [k].rotation = quater;
			
			}

		}
	}
		

	void GUIButtonControl()
	{
		//simple function that disables/enables GUI buttons when we need and dont need them.
		if (mobileInput)
		{
			gasPedal.gameObject.SetActive(true);
			leftPedal.gameObject.SetActive(true);
			rightPedal.gameObject.SetActive(true);
			brakePedal.gameObject.SetActive(true);
            buttonA.gameObject.SetActive(true);
        }
		else{
			gasPedal.gameObject.SetActive(false);
			leftPedal.gameObject.SetActive(false);
			rightPedal.gameObject.SetActive(false);
			brakePedal.gameObject.SetActive(false);
            buttonA.gameObject.SetActive(false);
        }
	}

	void DriveMobile()
	{
		if (!mobileInput)
			return;
		//dont call this function if the mobileiput box is not checked in the editor
		float gasMultiplier = 0f;

		if (!reversing) {
			if (currentSpeed < maxSpeed)
				gasMultiplier = 1f;
			else
				gasMultiplier = 0f;

		} else {
			if (currentSpeed < maxReverseSpeed)
				gasMultiplier = 1f;
			else
				gasMultiplier = 0f;
		}
		foreach (Touch touch in Input.touches) {

			//if the gas button is pressed down, speed up the car.
			if (touch.phase == TouchPhase.Stationary && gasPedal.HitTest(touch.position))
			{
				throttleInput = 1;
			}
			//when the gas button is released, slow the car down
			else if (touch.phase == TouchPhase.Ended && gasPedal.HitTest(touch.position))
			{
				throttleInput = 0;
			}
			//now the same thing for the brakes
			if (touch.phase == TouchPhase.Stationary && brakePedal.HitTest(touch.position))
			{
				throttleInput = -1;
			}
			//stop braking once you put your finger off the brake pedal
			else if (touch.phase == TouchPhase.Ended && brakePedal.HitTest(touch.position))
			{
				throttleInput = 0;
			}
			//now the left steering column...
			if (touch.phase == TouchPhase.Stationary && leftPedal.HitTest(touch.position))
			{
				//turn the front left wheels according to input direction
				steerInput = -1;
			}
			//and stop the steering once you take your finger off the turn button
			else if (touch.phase == TouchPhase.Ended && leftPedal.HitTest(touch.position))
			{
				steerInput = 0;
			}
			//now the right steering column...
			if (touch.phase == TouchPhase.Stationary && rightPedal.HitTest(touch.position))
			{
				//turn the front left wheels according to input direction
				steerInput = 1;
			}
			//and stop the steering once you take your finger off the turn button
			else if (touch.phase == TouchPhase.Ended && rightPedal.HitTest(touch.position))
			{
				steerInput = 0; 
			}

            if (touch.phase == TouchPhase.Stationary && buttonA.HitTest(touch.position))
            {
                //turn the front left wheels according to input direction
            

            dir = Vector3.zero;

            dir.x = -Input.acceleration.x;




            if (dir.x > 0)
            {

                steerInput = -1;

            }

            else if (dir.x < 0)
            {

                steerInput = 1;

            }


                
            }



            /*
            else
            {
                steerInput = 0;
            }
            */
            //now that we have our input values made, it's time to feed them to the car!
            wheels.wheelFL.steerAngle = maxSteer * steerInput;
			wheels.wheelFR.steerAngle = maxSteer * steerInput;
			//`````````````````````````````````````````````
			if (DriveTrain == DriveType.RWD)
			{
				wheels.wheelRL.motorTorque = maxTorque * throttleInput * gasMultiplier;
				wheels.wheelRR.motorTorque = maxTorque * throttleInput * gasMultiplier;

				if (localCurrentSpeed.z < -0.1f && wheels.wheelRL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
					reversing = true;
				} else {
					reversing = false;
				}
			}
			if (DriveTrain == DriveType.FWD)
			{
				wheels.wheelFL.motorTorque = maxTorque * throttleInput * gasMultiplier;
				wheels.wheelFR.motorTorque = maxTorque * throttleInput * gasMultiplier;

				if (localCurrentSpeed.z < -0.1f && wheels.wheelFL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
					reversing = true;
				} else {
					reversing = false;
				}
			}
			if (DriveTrain == DriveType.AWD)
			{
				wheels.wheelFL.motorTorque = maxTorque * throttleInput * gasMultiplier;
				wheels.wheelFR.motorTorque = maxTorque * throttleInput * gasMultiplier;
				wheels.wheelRL.motorTorque = maxTorque * throttleInput * gasMultiplier;
				wheels.wheelRR.motorTorque = maxTorque * throttleInput * gasMultiplier;

				if (localCurrentSpeed.z < -0.1f && wheels.wheelRL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
					reversing = true;
				} else {
					reversing = false;
				}
			}

		}

       


    }

    void Drive()
	{
		if (mobileInput)
			return;
		//dont call this function if mobile input is checked in the editor
		float gasMultiplier = 0f;

		if (!reversing) {
			if (currentSpeed < maxSpeed)
				gasMultiplier = 1f;
			else
				gasMultiplier = 0f;

		} else {
			if (currentSpeed < maxReverseSpeed)
				gasMultiplier = 1f;
			else
				gasMultiplier = 0f;
		}
		//the car will be 4 wheel drive or else it will be slow or feel a little sluggish
		//no matter how much you increase the max torque.
		if (DriveTrain == DriveType.RWD)
		{
			wheels.wheelRR.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;
			wheels.wheelRL.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;

			if (localCurrentSpeed.z < -0.1f && wheels.wheelRL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
				reversing = true;
			} else {
				reversing = false;
			}
		}
		if (DriveTrain == DriveType.FWD)
		{
			wheels.wheelFL.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;
			wheels.wheelFR.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;

			if (localCurrentSpeed.z < -0.1f && wheels.wheelFL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
				reversing = true;
			} else {
				reversing = false;
			}
		}
		if (DriveTrain == DriveType.AWD)
		{

			wheels.wheelFL.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;
			wheels.wheelFR.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;
			wheels.wheelRL.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;
			wheels.wheelRR.motorTorque = maxTorque * Input.GetAxis("Vertical") * gasMultiplier;

			if (localCurrentSpeed.z < -0.1f && wheels.wheelRL.rpm < 10) {//in local space, if the car is travelling in the direction of the -z axis, (or in reverse), reversing will be true
				reversing = true;
			} else {
				reversing = false;
			}
		}


