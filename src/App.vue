<template>
  <v-app>
    <!-- Header -->
    <v-app-bar
      :elevation="0"
      color="transparent"
      class="header-bar"
      height="80"
    >
      <v-container class="d-flex align-center">
        <div class="d-flex align-center">
          <BeijaFlorLogo class="mr-3" />
          <v-app-bar-title class="logo-text">
            Beija-Flor
          </v-app-bar-title>
        </div>
        <v-spacer />
        <v-btn
          variant="outlined"
          color="white"
          class="contact-btn"
        >
          Entre em contato
        </v-btn>
      </v-container>
    </v-app-bar>

    <!-- Main Content -->
    <v-main>
      <!-- Hero Section -->
      <section class="hero-section">
        <v-container>
          <v-row align="center" class="fill-height">
            <v-col cols="12" md="6">
              <h1 class="hero-title mb-4">
                Projeto Beija-Flor
              </h1>
              <p class="hero-subtitle mb-8">
                A estrutura padrão de um projeto usando o
                Docker para facilitar o desenvolvimento e
                implantação de aplicações.
              </p>
              <v-btn
                color="white"
                size="large"
                class="hero-btn"
              >
                Saiba mais
              </v-btn>
            </v-col>
            <v-col cols="12" md="6" class="text-center">
              <DeveloperIllustration />
            </v-col>
          </v-row>
        </v-container>
      </section>

      <!-- Features Section -->
      <section class="features-section py-16">
        <v-container>
          <div class="text-center mb-12">
            <h2 class="section-title">Principais características</h2>
            <div class="title-underline mx-auto"></div>
          </div>
          
          <v-row>
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <SecurityIcon />
              </div>
              <h3 class="feature-title mb-3">Vários recursos</h3>
              <p class="feature-description">
                Nosso SDK de diversas funcionalidades e opções de personalização para atender às suas necessidades específicas
              </p>
            </v-col>
            
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <MessageIcon />
              </div>
              <h3 class="feature-title mb-3">Serviço de mensageria</h3>
              <p class="feature-description">
                Facilite o desenvolvimento e a implantação de suas aplicações de forma simples e rápida através de um SDK eficiente
              </p>
            </v-col>
            
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <DatabaseIcon />
              </div>
              <h3 class="feature-title mb-3">Base de dados</h3>
              <p class="feature-description">
                Integre-se à infraestrutura existente sem complicações. Nosso SDK é projetado para ser flexível e adaptável
              </p>
            </v-col>
          </v-row>

          <v-row class="mt-8">
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <EmailIcon />
              </div>
              <h3 class="feature-title mb-3">E-mail</h3>
              <p class="feature-description">
                É obrigatório de mais que o sistema tenha uma API para envio de e-mails e informações
              </p>
            </v-col>
            
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <WebIcon />
              </div>
              <h3 class="feature-title mb-3">Mensageria</h3>
              <p class="feature-description">
                Nossos sistema oferece a facilidade para usar com sua nova API para controle de uso da aplicação
              </p>
            </v-col>
            
            <v-col cols="12" md="4" class="text-center mb-8">
              <div class="feature-icon mb-4">
                <DevelopmentIcon />
              </div>
              <h3 class="feature-title mb-3">Desenvolvimento ágil</h3>
              <p class="feature-description">
                Desenvolvimento otimizado e robusto para todas as necessidades de sua empresa. Nosso SDK e integração
              </p>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <!-- 5 Motivos Section -->
      <section class="reasons-section py-16 bg-grey-lighten-5">
        <v-container>
          <div class="text-center mb-12">
            <h2 class="section-title">5 motivos para escolher o SDK em Golang</h2>
          </div>
          
          <v-row>
            <v-col cols="12" md="6" class="mb-8">
              <div class="reason-item d-flex">
                <div class="reason-number mr-4">01</div>
                <div>
                  <h3 class="reason-title mb-3">Velocidade e desempenho</h3>
                  <p class="reason-description">
                    Com o Golang Prognet, você terá muito desempenho nas suas aplicações mais importantes e integração fluida. É uma excelente solução com fácil implementação para os mais diversos types de projetos.
                  </p>
                </div>
              </div>
            </v-col>
            
            <v-col cols="12" md="6" class="mb-8">
              <div class="reason-item d-flex">
                <div class="reason-number mr-4">02</div>
                <div>
                  <h3 class="reason-title mb-3">Facilidade de uso</h3>
                  <p class="reason-description">
                    Com o Golang Prognet, você pode aplicar em qualquer projeto A.I., Nos ajude aplicada com melhor controle através do desenvolvimento facilitado no nosso framework APIs simples e intuitiva.
                  </p>
                </div>
              </div>
            </v-col>
            
            <v-col cols="12" md="6" class="mb-8">
              <div class="reason-item d-flex">
                <div class="reason-number mr-4">03</div>
                <div>
                  <h3 class="reason-title mb-3">Compatibilidade</h3>
                  <p class="reason-description">
                    Nosso SDK é totalmente compatível com os principais sistemas e plataformas, garantindo que sua aplicação funcione perfeitamente em qualquer ambiente de desenvolvimento ou produção.
                  </p>
                </div>
              </div>
            </v-col>
            
            <v-col cols="12" md="6" class="mb-8">
              <div class="reason-item d-flex">
                <div class="reason-number mr-4">04</div>
                <div>
                  <h3 class="reason-title mb-3">Comunidade ativa e suporte</h3>
                  <p class="reason-description">
                    Conte com uma comunidade ativa de desenvolvedores e nosso suporte técnico especializado. Documentação completa e exemplos práticos para acelerar seu desenvolvimento.
                  </p>
                </div>
              </div>
            </v-col>
            
            <v-col cols="12" class="mb-8">
              <div class="reason-item d-flex">
                <div class="reason-number mr-4">05</div>
                <div>
                  <h3 class="reason-title mb-3">Suporte e atualizações crescentes</h3>
                  <p class="reason-description">
                    Nossa equipe de desenvolvimento trabalha constantemente para melhorar o SDK, adicionando novas funcionalidades e corrigindo bugs. Receba atualizações regulares e mantenha sua aplicação sempre atual.
                  </p>
                </div>
              </div>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <!-- Community Section -->
      <section class="community-section py-16">
        <v-container>
          <div class="text-center">
            <h2 class="section-title mb-4">Junte-se à comunidade</h2>
            <p class="community-description mb-8">
              Faça parte de uma comunidade ativa que está construindo aplicações robustas. 95% dos usuários que fizeram nossos programas trabalham com maior facilidade. Temos uma comunidade ativa que está sempre disponível para ajudar e compartilhar conhecimento.
            </p>
            <v-btn color="primary" size="large" class="join-btn">
              Participar
            </v-btn>
          </div>
        </v-container>
      </section>

      <!-- Plans Section -->
      <section class="plans-section py-16 bg-grey-lighten-5">
        <v-container>
          <v-row justify="center">
            <!-- Free Plan -->
            <v-col cols="12" md="5" class="mb-8">
              <v-card class="plan-card free-plan" elevation="2">
                <v-card-text class="pa-8 text-center">
                  <h3 class="plan-title mb-4">Plano gratuito</h3>
                  <p class="plan-description mb-6">
                    Para começar a explorar nosso SDK
                  </p>
                  
                  <v-list class="plan-features">
                    <v-list-item class="feature-item">
                      <template v-slot:prepend>
                        <v-icon color="success">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Integrações por mês limitadas</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item">
                      <template v-slot:prepend>
                        <v-icon color="success">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Exemplos e documentação básica</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item">
                      <template v-slot:prepend>
                        <v-icon color="success">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Suporte da comunidade</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item">
                      <template v-slot:prepend>
                        <v-icon color="success">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Recursos básicos de mensageria</v-list-item-title>
                    </v-list-item>
                  </v-list>
                  
                  <v-btn variant="outlined" color="primary" size="large" class="mt-6">
                    Começar
                  </v-btn>
                </v-card-text>
              </v-card>
            </v-col>

            <!-- Premium Plan -->
            <v-col cols="12" md="5" class="mb-8">
              <v-card class="plan-card premium-plan" elevation="8">
                <div class="popular-badge">
                  <span>MAIS POPULAR</span>
                </div>
                <v-card-text class="pa-8 text-center text-white">
                  <h3 class="plan-title mb-4">Plano avançado</h3>
                  <p class="plan-description mb-6">
                    Para empresas e desenvolvedores profissionais
                  </p>
                  
                  <v-list class="plan-features transparent">
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Acesso a recursos avançados</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Acesso a recursos limitados</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Suporte técnico prioritário</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Integração avançada de e-mail</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Recursos avançados de mensageria</v-list-item-title>
                    </v-list-item>
                    <v-list-item class="feature-item text-white">
                      <template v-slot:prepend>
                        <v-icon color="white">mdi-check-circle</v-icon>
                      </template>
                      <v-list-item-title>Análises e relatórios detalhados</v-list-item-title>
                    </v-list-item>
                  </v-list>
                  
                  <v-btn color="white" size="large" class="mt-6 premium-btn">
                    Adquirir
                  </v-btn>
                </v-card-text>
              </v-card>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <!-- Purpose Section -->
      <section class="purpose-section py-16">
        <v-container>
          <div class="text-center mb-12">
            <h2 class="section-title">Qual o nosso propósito?</h2>
            <div class="title-underline mx-auto"></div>
          </div>
          
          <v-row align="center">
            <v-col cols="12" md="6">
              <PurposeIllustration />
            </v-col>
            <v-col cols="12" md="6">
              <div class="purpose-content">
                <div class="purpose-item mb-6">
                  <div class="d-flex align-center mb-3">
                    <MissionIcon class="mr-3" />
                    <h3 class="purpose-item-title">Missão</h3>
                  </div>
                  <p class="purpose-item-description">
                    Nosso objetivo é criar ferramentas e soluções que facilitam o desenvolvimento de aplicações robustas e escaláveis.
                  </p>
                </div>
                
                <div class="purpose-item mb-6">
                  <div class="d-flex align-center mb-3">
                    <VisionIcon class="mr-3" />
                    <h3 class="purpose-item-title">Visão</h3>
                  </div>
                  <p class="purpose-item-description">
                    Tornar-se a principal referência em SDKs e ferramentas de desenvolvimento para a comunidade Golang.
                  </p>
                </div>
                
                <div class="purpose-item">
                  <div class="d-flex align-center mb-3">
                    <ValuesIcon class="mr-3" />
                    <h3 class="purpose-item-title">Valores</h3>
                  </div>
                  <p class="purpose-item-description">
                    Simplicidade, eficiência, qualidade e transparência são os pilares que guiam nosso trabalho diário.
                  </p>
                </div>
              </div>
            </v-col>
          </v-row>
        </v-container>
      </section>

      <!-- Contact Section -->
      <section class="contact-section py-16 bg-grey-lighten-5">
        <v-container>
          <v-row align="center">
            <v-col cols="12" md="6">
              <h2 class="contact-title mb-4">Fale com a gente</h2>
              <p class="contact-description mb-8">
                Estamos prontos para ajudar a conectar a sua equipe de forma mais eficiente. Entre em contato conosco para saber mais sobre nossas soluções.
              </p>
              
              <v-form>
                <v-row>
                  <v-col cols="12" md="6">
                    <v-text-field
                      label="Nome"
                      variant="outlined"
                      density="comfortable"
                    />
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-text-field
                      label="Email"
                      variant="outlined"
                      density="comfortable"
                    />
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="12" md="6">
                    <v-text-field
                      label="Telefone"
                      variant="outlined"
                      density="comfortable"
                    />
                  </v-col>
                  <v-col cols="12" md="6">
                    <v-text-field
                      label="Empresa"
                      variant="outlined"
                      density="comfortable"
                    />
                  </v-col>
                </v-row>
                <v-row>
                  <v-col cols="12">
                    <v-btn color="primary" size="large">
                      Enviar
                    </v-btn>
                  </v-col>
                </v-row>
              </v-form>
            </v-col>
            <v-col cols="12" md="6" class="text-center">
              <ContactIllustration />
            </v-col>
          </v-row>
        </v-container>
      </section>
    </v-main>

    <!-- Footer -->
    <v-footer class="footer bg-primary">
      <v-container>
        <v-row align="center">
          <v-col cols="12" md="6">
            <div class="d-flex align-center text-white">
              <BeijaFlorLogo class="mr-3" />
              <span class="footer-logo-text">Beija-Flor</span>
            </div>
          </v-col>
          <v-col cols="12" md="6" class="text-right">
            <p class="footer-text mb-0">ESCOLHA SUA OPÇÃO</p>
          </v-col>
        </v-row>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>
import BeijaFlorLogo from './components/icons/BeijaFlorLogo.vue'
import DeveloperIllustration from './components/icons/DeveloperIllustration.vue'
import SecurityIcon from './components/icons/SecurityIcon.vue'
import MessageIcon from './components/icons/MessageIcon.vue'
import DatabaseIcon from './components/icons/DatabaseIcon.vue'
import EmailIcon from './components/icons/EmailIcon.vue'
import WebIcon from './components/icons/WebIcon.vue'
import DevelopmentIcon from './components/icons/DevelopmentIcon.vue'
import PurposeIllustration from './components/icons/PurposeIllustration.vue'
import ContactIllustration from './components/icons/ContactIllustration.vue'
import MissionIcon from './components/icons/MissionIcon.vue'
import VisionIcon from './components/icons/VisionIcon.vue'
import ValuesIcon from './components/icons/ValuesIcon.vue'

export default {
  name: 'App',
  components: {
    BeijaFlorLogo,
    DeveloperIllustration,
    SecurityIcon,
    MessageIcon,
    DatabaseIcon,
    EmailIcon,
    WebIcon,
    DevelopmentIcon,
    PurposeIllustration,
    ContactIllustration,
    MissionIcon,
    VisionIcon,
    ValuesIcon
  }
}
</script>

<style scoped>
/* Header Styles */
.header-bar {
  background: linear-gradient(135deg, #3B4A6B 0%, #2C3E50 100%) !important;
}

.logo-text {
  color: white !important;
  font-weight: 600;
  font-size: 1.5rem;
}

.contact-btn {
  border-color: white !important;
  color: white !important;
}

/* Hero Section */
.hero-section {
  background: linear-gradient(135deg, #3B4A6B 0%, #2C3E50 100%);
  color: white;
  min-height: 600px;
  display: flex;
  align-items: center;
  padding: 100px 0;
}

.hero-title {
  font-size: 3rem;
  font-weight: 700;
  line-height: 1.2;
}

.hero-subtitle {
  font-size: 1.2rem;
  line-height: 1.6;
  opacity: 0.9;
}

.hero-btn {
  color: #3B4A6B !important;
  font-weight: 600;
  padding: 15px 30px;
}

/* Features Section */
.features-section {
  background: white;
}

.section-title {
  font-size: 2.5rem;
  font-weight: 700;
  color: #2C3E50;
  margin-bottom: 1rem;
}

.title-underline {
  width: 60px;
  height: 4px;
  background: #5E72E4;
  margin-bottom: 2rem;
}

.feature-icon {
  width: 80px;
  height: 80px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
  background: #F8F9FA;
  border-radius: 50%;
}

.feature-title {
  font-size: 1.4rem;
  font-weight: 600;
  color: #2C3E50;
}

.feature-description {
  color: #6C757D;
  line-height: 1.6;
}

/* Reasons Section */
.reasons-section {
  background: #F8F9FA;
}

.reason-item {
  background: white;
  padding: 30px;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.08);
  height: 100%;
}

.reason-number {
  background: #5E72E4;
  color: white;
  width: 50px;
  height: 50px;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-weight: 700;
  font-size: 1.2rem;
  flex-shrink: 0;
}

.reason-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: #2C3E50;
}

.reason-description {
  color: #6C757D;
  line-height: 1.6;
}

/* Community Section */
.community-section {
  background: white;
}

.community-description {
  font-size: 1.1rem;
  color: #6C757D;
  line-height: 1.6;
  max-width: 800px;
  margin: 0 auto;
}

.join-btn {
  padding: 15px 40px;
  font-weight: 600;
}

/* Plans Section */
.plans-section {
  background: #F8F9FA;
}

.plan-card {
  height: 100%;
  position: relative;
  border-radius: 20px !important;
}

.free-plan {
  background: white;
}

.premium-plan {
  background: linear-gradient(135deg, #5E72E4 0%, #3B4A6B 100%);
  position: relative;
}

.popular-badge {
  position: absolute;
  top: -15px;
  left: 50%;
  transform: translateX(-50%);
  background: #11CDEF;
  color: white;
  padding: 8px 20px;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
}

.plan-title {
  font-size: 1.8rem;
  font-weight: 700;
}

.plan-description {
  font-size: 1.1rem;
  opacity: 0.8;
}

.plan-features {
  background: transparent !important;
}

.feature-item {
  padding: 8px 0;
}

.premium-btn {
  color: #5E72E4 !important;
  font-weight: 600;
}

/* Purpose Section */
.purpose-section {
  background: white;
}

.purpose-item-title {
  font-size: 1.3rem;
  font-weight: 600;
  color: #2C3E50;
}

.purpose-item-description {
  color: #6C757D;
  line-height: 1.6;
}

/* Contact Section */
.contact-section {
  background: #F8F9FA;
}

.contact-title {
  font-size: 2.5rem;
  font-weight: 700;
  color: #2C3E50;
}

.contact-description {
  font-size: 1.1rem;
  color: #6C757D;
  line-height: 1.6;
}

/* Footer */
.footer {
  padding: 40px 0;
}

.footer-logo-text {
  font-size: 1.5rem;
  font-weight: 600;
}

.footer-text {
  color: rgba(255,255,255,0.8);
}

/* Responsive */
@media (max-width: 960px) {
  .hero-title {
    font-size: 2.5rem;
  }
  
  .section-title {
    font-size: 2rem;
  }
  
  .reason-item {
    margin-bottom: 20px;
  }
}

@media (max-width: 600px) {
  .hero-title {
    font-size: 2rem;
  }
  
  .section-title {
    font-size: 1.8rem;
  }
  
  .hero-section {
    padding: 60px 0;
  }
}
</style> 