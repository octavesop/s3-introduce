
    <template>
  <v-card
    :loading="loading"
    class="mx-auto my-12"
    max-width="600"
  >
    <template slot="progress">
      <v-progress-linear
        color="deep-purple"
        height="10"
        indeterminate
      ></v-progress-linear>
    </template>

    <v-card-text>
      <v-row
        align="center"
        class="mb-3"
      >
        <v-img 
          src="@/assets/profile.png"
          class="ma-2"
          max-height="180"
          max-width="180"
        />
          
          <v-col>
            <h1>Jung Mina</h1>
            <span class=ma-3>Web-Developer</span>
            <v-divider class="mt-3 mb-3"/>
            <div>
              <v-chip class=mr-1>JavaScript</v-chip>
              <v-chip class=mr-1>Node.js</v-chip>
              <v-chip class=mr-1>Vue.js</v-chip>
              <v-chip class=mr-1>Flutter</v-chip>
              
              <br>
              <v-chip class="mr-1 mt-1">Git</v-chip>
              <v-chip class="mr-1 mt-1">Github</v-chip>
              <v-chip class=mr-1>MySQL</v-chip>
              <v-chip class="mr-1 mt-1">Linux</v-chip>
              <v-chip class="mr-1 mt-1">AWS</v-chip>
            </div>
          </v-col>
      </v-row>
      <v-divider class="mb-5"/>
      <div>
        15살, 정보 시간의 비주얼 코딩에서 시작해 백엔드 개발자의 꿈을 갖게 되었습니다.<br>
        모두 함께 나아가는 과정과 소통을 중요하게 여기고, <br>
        언제든지, 어느 방향에서든지 더 나아가기 위해 힘씁니다. <br>
      </div>
      <v-divider class="mt-5 mb-5"/>
      <div class="ma-2">
        <h2 class="mb-1">광주소프트웨어마이스터고등학교</h2>
        <div class="ml-3">2018.03 ~ 2021.02</div>
        <ul class="ma-2">
          <li>자료구조, 네트워크, OS와 같은 이론 과목 이수</li>
          <li>웹 개발 동아리 부장 담당 / GSM 해커톤 등 참여</li>
        </ul>
        <br>
        <h2 class="mb-1">방송통신대학교 / 컴퓨터과학과</h2>
        <div class="ml-3">2021.03 ~ (재학중)</div>
        <v-divider class="mt-5 mb-5"/>
        <h2 class="mb-1">(주)나무인텔리전스 / Fullstack Developer</h2>
        <div class="ml-3">2020.11 ~ 2021.05</div>
        <ul class="ma-2">
          <li>헬스케어 앱 EZFit 개발</li>
          <li>앱 전용 API 서버 개발</li>
          <li>Notion을 활용한 문서화, Github 관리 담당</li>
        </ul>
      </div>
      <div>자세한 내용은 <a href="https://www.notion.so/d40739aa0d284cc897348405634a366c">Notion</a>에서 더 보실 수 있어요!</div>
      
    </v-card-text>

    <v-divider class="mx-4"></v-divider>

  </v-card>
</template>

<script>

export default {
}
</script>
