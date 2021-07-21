<template>


<v-row  class="d-flex justify-center">
    <v-col cols="12"
            md="6" lg="6">
            
  <div>
      <span class="text-h3">My experience</span>
    <v-switch
      v-model="reverse"
      label="Toggle reverse"
    ></v-switch>
    <v-timeline
      :reverse="reverse"
      :dense="$vuetify.breakpoint.smAndDown"
    >
     
      <v-timeline-item>
           <span slot="opposite">May 2021 - August 2021</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="https://pbs.twimg.com/profile_images/1203099554742177794/PVSPnAuD_400x400.jpg"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
            Omnicell
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Software Engineer Intern
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
             My first real internship! I helped the Guided Packing team cut down on manual data requests by building a data analytics dashboard. 
              This dashboard helped the team be more proactive in their support decisions, saving both them and the customers valuable time. I learned a lot technology-wise, 
              (ASP.NET, Vue.js, Vuetify, SQL Server, Dapper ORM) but also so much more when it came to working in a team environment. This experience only made me more excited to grow as a developer. 
          </v-card-text>
          
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
           <span slot="opposite">December 2020 - April 2021</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="https://flowimage.flow.page/resize?img=https%3A%2F%2Fcdn.flow.page%2Fimages%2F6c2e6cf9-5573-4ba9-a452-259d18503078-profile-picture%3Fm%3D1606514937&w=320"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
            James Street Sensory
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Front End Developer
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
             James Street is an organization focused on raising awareness for children/people on the autism spectrum. When it came to redesigning their website
              I had a lot of time to think about the best way to represent their brand. They wanted something local, vibrant, and indicative of autism awareness.
              I chose to go with Google's Material Design language, incorporating colors that represented autism and also used local images to bring it all together. 
              This experience was more than just building a website, I learned how much it meant to contribute to something meaningful. 
          </v-card-text>
          
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
           <span slot="opposite">June 2020 - September 2020</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="https://media.wired.com/photos/5926ffe47034dc5f91bed4e8/master/w_1920,c_limit/google-logo.jpg"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
            Google CSSI
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Student
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
              Before I started college, I had the privilege to participate in Google's Computer Science Summer Institute. This program is an 8 week, intensive and collaborative software and career development program led by
Google Engineers for high-achieving diverse talent based on academic success and career ambition. It was remote but still had a great time. 
          </v-card-text>
          
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
           <span slot="opposite">September 2020</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="https://upload.wikimedia.org/wikipedia/en/thumb/f/fb/University_of_Pittsburgh_seal.svg/150px-University_of_Pittsburgh_seal.svg.png"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
           University of Pittsburgh
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Commited! 
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
              Hail to Pitt! Happy to be spending the next 4 here. 
          </v-card-text>
          
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
           <span slot="opposite">June 2019 - August 2019</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="https://upload.wikimedia.org/wikipedia/en/thumb/f/fb/University_of_Pittsburgh_seal.svg/150px-University_of_Pittsburgh_seal.svg.png"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
           Hillman Cancer Center
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Computational Biology Researcher 
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
             I developed an Electrocardiogram device that could classify a patient's heartbeat arrhythmia in real-time! I learned Python data manipulation and machine learning libraries such as pandas and NumPy. I worked with my team who guided me along the way. As a junior in high school, given any amount of real responsibility seemed daunting. I learned how applicable my research was which was a great sight to see. I also won an award
              for the best CompBio project! 

          </v-card-text>
          
        </v-card>
      </v-timeline-item>
      <v-timeline-item>
           <span slot="opposite">August 2016 - June 2020</span>
        <v-card class="elevation-2">
            <v-card-actions>
                <v-list-item-avatar color=" ml-3 ">
          <v-img
            class="elevation-6"
            alt=""
            src="data:image/jpeg;base64,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"
          ></v-img>
        </v-list-item-avatar>
        <v-card-title class=" ml-n2 text-h5">
           North Allegheny High School
          </v-card-title>
          
            </v-card-actions>
          <v-card-text class="mt-n5 font-italic">
              Student
          </v-card-text>
          <v-card-text class="mt-n4 font-weight-regular">
             I learned about computer science in 9th grade. Also, ran Varsity Track & Field and Cross Country. 
          </v-card-text>
          
        </v-card>
      </v-timeline-item>
     
    </v-timeline>
    
  </div>
  </v-col></v-row>
  
</template>

<script>
export default {
     name: 'Timeline',
data: () => ({
      reverse: true,
    }),
}
</script>

<style>

</style>