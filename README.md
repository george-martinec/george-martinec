```php
<?php

declare(strict_types = 1);

namespace GeorgeMartinec;

class About extends Me
{
    /**
     * @return array<string, string>
     */
    public function getCurrentWorkplace(): array
    {
        return [
            'company' => 'SIMPLO s.r.o.',
            'position' => 'Backend PHP Developer',         
        ];
    }

    /**
     * @return array<array-key, class-string>
     */
    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Laravel::class,
            MySQL::class,
            Docker::class,
            Git::class,
            ...$this->getAdditionalDailyKnowledge(),
        ];
    }

    /**
     * @return string
     */
    public function getFutureGoal(): string
    {
        return 'Contribute to open source';
    }
}
```

<br>
<div align="center">
    <code><img height="32" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain-wordmark.svg" alt="Laravel" title="Laravel" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192107854-765620d7-f909-4953-a6da-36e1ef69eea6.png" alt="HTTP" title="HTTP" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/187070862-03888f18-2e63-4332-95fb-3ba4f2708e59.png" alt="websocket" title="websocket" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192107858-fe19f043-c502-4009-8c47-476fc89718ad.png" alt="REST" title="REST" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192107860-9a9f0894-0e34-4ab3-964d-6297ee4c00e9.png" alt="SOAP" title="SOAP" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108372-f71d70ac-7ae6-4c0d-8395-51d8870c2ef0.png" alt="Git" title="Git" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png" alt="GitHub" title="GitHub" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108376-c675d39b-90f6-4073-bde6-5a9291644657.png" alt="GitLab" title="GitLab" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108375-268c35e6-ab26-44b2-88bf-e3121a4e5083.png" alt="Bitbucket" title="Bitbucket" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108889-232b3431-a585-4b36-a62d-9078bd3641d9.png" alt="Vim" title="Vim" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108893-b1eed3c7-b2c4-4e1c-9e9f-c7e83637b33d.png" alt="WebStorm" title="WebStorm" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108895-20dc3343-43e3-4a54-a90e-13a4abbc57b9.png" alt="Android Studio" title="Android Studio" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192108891-d86b6220-e232-423a-bf5f-90903e6887c3.png" alt="Visual Studio Code" title="Visual Studio Code" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/190887576-6653f877-8439-4521-82f3-403086ead892.png" alt="Sublime Text" title="Sublime Text" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192109061-e138ca71-337c-4019-8d42-4792fdaa7128.png" alt="Postman" title="Postman" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192158954-f88b5814-d510-4564-b285-dff7d6400dad.png" alt="HTML" title="HTML" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183898674-75a4a1b1-f960-4ea9-abcb-637170a00a75.png" alt="CSS" title="CSS" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192158956-48192682-23d5-4bfc-9dfb-6511ade346bc.png" alt="Sass" title="Sass" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183898054-b3d693d4-dafb-4808-a509-bab54cf5de34.png" alt="Bootstrap" title="Bootstrap" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/202896760-337261ed-ee92-4979-84c4-d4b829c7355d.png" alt="Tailwind CSS" title="Tailwind CSS" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192158957-b1256181-356c-46a3-beb9-487af08a6266.png" alt="Wordpress" title="Wordpress" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/186711335-a3729606-5a78-4496-9a36-06efcc74f800.png" alt="Swagger" title="Swagger" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/187955001-20e6d7d2-d8ba-49aa-8fd7-2d8b1f49f556.png" alt="Browsersync" title="Browsersync" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/189716855-2c69ca7a-5149-4647-936d-780610911353.png" alt="Firebase" title="Firebase" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/189715289-df3ee512-6eca-463f-a0f4-c10d94a06b2f.png" alt="Figma" title="Figma" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/189716058-71f74b6f-5936-40b5-92e3-00381e35ccb9.png" alt="Material Design" title="Material Design" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/189716630-fe6c084c-6c66-43af-aa49-64c8aea4a5c2.png" alt="Material UI" title="Material UI" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/117447155-6a868a00-af3d-11eb-9cfe-245df15c9f3f.png" alt="JavaScript" title="JavaScript" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/117448124-a2da9800-af3e-11eb-85d2-bd1b69b65603.png" alt="Vue.js" title="Vue.js" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183890598-19a0ac2d-e88a-4005-a8df-1ee36782fde1.png" alt="TypeScript" title="TypeScript" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/121401671-49102800-c959-11eb-9f6f-74d49a5e1774.png" alt="npm" title="npm" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183049794-a3dfaddd-22ee-4ffe-b0b4-549ccd4879f9.png" alt="yarn" title="yarn" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/187955008-981340e6-b4cc-441b-80cf-7a5e94d29e7e.png" alt="webpack" title="webpack" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183570228-6a040b9f-3ddf-47a2-a201-743121dac664.png" alt="php" title="php" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/117208740-bfb78400-adf5-11eb-97bb-09072b6bedfc.png" alt="PostgreSQL" title="PostgreSQL" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183896128-ec99105a-ec1a-4d85-b08b-1aa1620b2046.png" alt="MySQL" title="MySQL" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/182884894-d3fa6ee0-f2b4-4960-9961-64740f533f2a.png" alt="redis" title="redis" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/182884177-d48a8579-2cd0-447a-b9a6-ffc7cb02560e.png" alt="mongoDB" title="mongoDB" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/192158606-7c2ef6bd-6e04-47cf-b5bc-da2797cb5bda.png" alt="bash" title="bash" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/117207330-263ba280-adf4-11eb-9b97-0ac5b40bc3be.png" alt="Docker" title="Docker" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/182534075-4962068b-4407-46c2-ac67-ddcb86af30cc.png" alt="Grafana" title="Grafana" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/182534182-c510199a-7a4d-4084-96e3-e3db2251bbce.png" alt="Prometheus" title="Prometheus" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183345125-9a7cd2e6-6ad6-436f-8490-44c903bef84c.png" alt="Nginx" title="Nginx" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/183569191-f32cdf03-673f-4ae3-809b-3a8b376bb8a2.png" alt="Elasticsearch" title="Elasticsearch" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/186884150-05e9ff6d-340e-4802-9533-2c3f02363ee3.png" alt="Windows" title="Windows" /></code>
	<code><img height="32" src="https://user-images.githubusercontent.com/25181517/186884153-99edc188-e4aa-4c84-91b0-e2df260ebc33.png" alt="Ubuntu" title="Ubuntu" /></code>
<code><img height="32" src="https://www.vectorlogo.zone/logos/circleci/circleci-icon.svg" alt="CircleCI" title="CircleCI" /></code>
 <h6>and many others ...</h6>
</div>
