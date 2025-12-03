<template>
  <BaseLayout>
    <div class="section-timeline-heading">
      <div class="container">
        <div class="padding-vertical-xlarge">
          <div class="timeline-main_heading-wrapper">
            <div class="margin-bottom-medium">
              <div class="timeline_date-text">Today</div>
            </div>
            <div class="margin-bottom-small">
              <div class="timeline_text">
                Today, I blend my tech skills and passion as a software
                engineer, adept in DevOps, cloud, and full-stack engineering. I
                nurture valuable connections and contribute to meaningful
                projects in the tech landscape.
              </div>
            </div>
            <div class="margin-bottom-large">
              <p class="paragraph-large">
                Explore my journey so far, and let's see how our paths can
                intersect.
              </p>
            </div>
            <a href="https://www.linkedin.com/in/r0a/" target="_blank" class="button-inverted w-button">
              Connect with me
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="section-timeline">
      <div class="container">
        <div class="timeline_component">
          <div class="timeline_progress">
            <div data-w-id="d5abcf1f-3370-3eea-ccfd-66f076babfdd" class="timeline_progress-bar"></div>
          </div>
          <div data-w-id="d5abcf1f-3370-3eea-ccfd-66f076babfe0" class="timeline_item">
            <div id="a" class="timeline_left">
              <div class="timeline_date-text">Q4 2025</div>
            </div>
            <div id="b" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div id="c" class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/application-observability.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Built service topology visualization and OpenTelemetry standardization pilot for Stablecoin
                  org's APM capabilities. Implemented service graph dependency maps with namespace tracking and
                  automatic instance identification across all environments.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/Grafana-Application-Observability-Icon.png" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Processing 2,800+ spans/second across all environments with peaks at 1,500+ spans/s in dev and 1,249
                    spans/s in staging. Configured
                    OpenTelemetry Operator resource attribute priority for outbound instance identification and
                    established cardinality management patterns preventing system degradation at scale.<br />
                  </p>
                  <p class="timeline_quote-title">APM Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="d5abcf1f-3370-3eea-ccfd-66f076babfe1" class="timeline_item">
            <div id="a" class="timeline_left">
              <div class="timeline_date-text">Q3 2025</div>
            </div>
            <div id="b" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div id="c" class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/logging-operator.svg" loading="lazy" width="180" alt=""
                  style="display: block; margin: 0 auto;" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Extended existing Logging Operator infrastructure to support dual-destination log forwarding
                  (Loki + S3) for Stablecoin security compliance. Collaborated with Infosec on IRSA cross-account
                  authentication eliminating node IAM role fallback. Configured ClusterOutput and ClusterFlow resources
                  with tuned buffer parameters and coordinated multi-day SIEM validation across all environments.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/s3-logo.svg" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Configured 10M chunk limits with 5GB buffer capacity, 10-thread flush processing, and 30 retry
                    attempts preventing data loss during ingestion. Established file-backed buffering with gzip
                    compression and block overflow protection. Pipeline now serves as the validated reference pattern
                    for compliance-driven dual-destination log exports.<br />
                  </p>
                  <p class="timeline_quote-title">Compliance Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="d5abcf1f-3370-3eea-ccfd-66f076babfe0" class="timeline_item">
            <div id="a" class="timeline_left">
              <div class="timeline_date-text">Q2 2025</div>
            </div>
            <div id="b" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div id="c" class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/grafana-mimir-logo.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Led observability cost optimization initiatives across metrics and logs. Identified ~18% of
                  unused
                  series through Adaptive Metrics analysis and implemented keep/drop rules with label aggregation.
                  Analyzed log query patterns to reduce Technical Services usage and establish guardrails.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/cost-logo.png" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Achieved 31% reduction in monthly observability costs (~$33k/mo savings) through targeted series
                    pruning and query optimization. Drove log spend down from ~$58k to ~$45k monthly while maintaining
                    operational visibility for engineering teams.<br />
                  </p>
                  <p class="timeline_quote-title">Cost Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="5b7ae63b-6f00-e542-a023-96ea5c4a96e4" class="timeline_item">
            <div id="d" class="timeline_left">
              <div class="timeline_date-text">Q1 2025</div>
            </div>
            <div id="e" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/argocd-k8s-logo.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Centralized Platform Operator deployment strategy by implementing RippleApplication →
                  ApplicationSet
                  translation. Built safe rollout mechanics with shadow/skip-reconcile support, enabling multi-cluster
                  consistency while preserving existing app-of-apps workflows.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/git-icon-logo.svg" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Reduced configuration drift across clusters by unifying GitOps control from a single plane. Teams
                    kept their existing orchestration patterns through annotation exceptions while gaining consistent
                    deployment guardrails and reduced operational overhead.<br />
                  </p>
                  <p class="timeline_quote-title">Platform Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="cea39288-a86d-bc98-0716-192fe18bb832" class="timeline_item">
            <div id="f" class="timeline_left">
              <div class="timeline_date-text">Q4 2024</div>
            </div>
            <div id="g" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/crossplane-logo.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Architected AWS SecretsManager Crossplane component enabling self-service infrastructure
                  provisioning
                  through Kubernetes-native interfaces. Built comprehensive TypeScript implementation with
                  template-based resource provisioning, validation, and environment-aware configurations.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/crossplane-icon.png" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Led knowledge transfer sessions enabling team members to develop their own Crossplane compositions,
                    establishing patterns for self-service infrastructure across the platform.<br />
                  </p>
                  <p class="timeline_quote-title">Knowledge Transfer<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="0488106f-ce92-9b7b-01c3-8ad75f3f5e37" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Also Q3 2024</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/wasm-envoy-logo.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Developed Slack Validator as a WebAssembly-based validation module running in Envoy Proxy,
                  implementing HMAC-SHA256 verification and timestamp validation for secure webhook integrations.
                  Created reusable security component for future API integrations.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/envoy-logo.png" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Established a reusable webhook security pattern that can be applied to future integrations like
                    GitLab and JIRA. Ensured cryptographic validation of all API requests before reaching backend
                    services, mitigating replay attacks and timing-based exploits.<br />
                  </p>
                  <p class="timeline_quote-title">Security Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="0488106f-ce92-9b7b-01c3-8ad75f3f5e36" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Q3 2024</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/loki-logo.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Built a Loki Forwarder using Fluent Bit to replace our expensive Sumo Logic setup for Auth0
                  logs. Deployed as a Kubernetes service with Helm charts, featuring HTTP endpoints protected by bearer
                  tokens and Istio virtual services for secure ingress.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/grafana-loki-logo.png" loading="lazy" width="50" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    Eliminated the last Sumo Logic dependency, contributing to $1M in annual cost savings. Engineering
                    teams now have centralized Auth0 event monitoring through Grafana with LogQL queries for compliance,
                    troubleshooting, and real-time alerting. <br />
                  </p>
                  <p class="timeline_quote-title">Business Impact<br /></p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="72497fc0-4591-9daf-81b3-b917784e7931" class="timeline_item">
            <div id="j" class="timeline_left">
              <div class="timeline_date-text">June 2024</div>
            </div>
            <div id="k" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/rippler.png" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  <br />Transitioned to full-time Software Engineer I at Ripple, expanding my role to leading critical
                  platform infrastructure initiatives. Took ownership of observability frameworks, cost optimization
                  strategies, and deployment automation serving Ripple's global engineering teams.<br />
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="d5abcf1f-3370-3eea-ccfd-66f076babfe1" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Summer 2023</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div id="n" class="timeline_right">
              <div class="timeline_image-wrapper">
                <img src="../../public/img/Ripple.svg" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-xlarge">
                <div class="timeline_text">
                  <br />At Ripple, I designed and implemented a
                  Kubernetes-native Vector Operator, achieving real-time log
                  routing from Kubernetes to Kafka. I introduced Vector,
                  VectorSource, and VectorSink CRDs, establishing dynamic
                  controllers for on-the-fly configuration. Through this
                  project, I transformed observability and fine-tuned system
                  monitoring, gaining unmatched experience.
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/vec.png" loading="lazy" width="50" alt="" class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    "The Vector Operator could be a game-changer in how we
                    handle and observe our systems, making our tasks smoother
                    and helping us catch issues faster. Our aim? Enhanced
                    Observability. From capturing real-time logs from Kubernetes
                    to Kafka, to offering clear insights and quick debugging,
                    we&#x27;re talking full coverage. With Vector as our
                    observability main component, it ensures a streamlined
                    process, less clutter, and a centralized tool approach. This
                    isn&#x27;t just about altering logs; it&#x27;s about
                    flexibility, control, and adapting quickly to our changing
                    needs."<br />
                  </p>
                  <p class="timeline_quote-title">Demo Excerpt<br /></p>
                </div>
              </div>
              <br />
              <div class="timeline_image-wrapper">
                <img src="../../public/img/eeevector-3.png" loading="lazy"
                  sizes="(max-width: 479px) 48px, (max-width: 767px) 64px, 36vw" alt="" width="425" srcset="
                    ../../public/img/eeevector-3-p-500.png  500w,
                    ../../public/img/eeevector-3-p-800.png  800w,
                    ../../public/img/eeevector-3.png       1006w
                  " />
              </div>
            </div>
          </div>
          <div data-w-id="5b7ae63b-6f00-e542-a023-96ea5c4a96e3" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Summer 2022</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  With Meta&#x27;s engineers, I built a scalable web app,
                  optimized server resources, and automated deployment via
                  CI/CD, gaining valuable mentorship.<br />
                </div>
              </div>
              <div class="margin-bottom-xlarge">
                <p class="text-colour-lightgrey">
                  The MLH Fellowship, a 12-week program backed by Meta, propels
                  aspiring engineers into the Production Engineering realm,
                  blending software and systems engineering to deliver reliable,
                  scalable tech services.<br />
                </p>
              </div>
              <div class="timeline_image-wrapper margin-bottom-medium">
                <img src="../../public/img/Meta.svg" loading="lazy" width="480" alt="" /><img
                  src="../../public/img/MLH.svg" loading="lazy" width="480" alt="" />
              </div>
              <div class="margin-bottom-xlarge">
                <div class="inline-block">
                  <a href="https://www.youtube.com/watch?v=Em4k8hM0urY&amp;t=1695s" target="_blank"
                    class="timeline_link w-inline-block">
                    <div>Featured in SREcon 2023 piece</div>
                    <img src="../../public/img/open_in_new.svg" loading="lazy" alt="" class="link-icon" />
                  </a>
                </div>
              </div>
              <div class="timeline_quote-wrapper">
                <img src="../../public/img/gornet_alex_200x230.jpg" loading="lazy" alt=""
                  class="timeline_quote-image" />
                <div class="timeline_quote-text-wrapper">
                  <p class="timeline_quote">
                    "[...] Roa, who used her knowledge gained in the program to
                    land an internship [...] the fellowship gave her access to
                    resources and mentorship she needed to learn about the field
                    and confidently pursue a role in it."<br />
                  </p>
                  <p class="timeline_quote-title">
                    Alex Gornet, Partner Success Manager at MLH<br />
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div data-w-id="cea39288-a86d-bc98-0716-192fe18bb831" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Also in Summer 2022</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="margin-bottom-xlarge">
                <div class="timeline_text">
                  During my EQ Bank DevOps &amp; Cloud Software Engineering
                  Internship, I focused on microservices infrastructure,
                  UI-based log monitoring, streamlining app releases using
                  Jenkins, and implementing anomaly alerts via Elasticsearch.<br />
                </div>
              </div>
              <div class="timeline_image-wrapper margin-bottom-medium">
                <img src="../../public/img/eq_appandcard.png" loading="lazy" width="480" alt="" />
              </div>
            </div>
          </div>
          <div data-w-id="0488106f-ce92-9b7b-01c3-8ad75f3f5e35" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Summer 2021</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  On a contracting gig at CIRID, I revamped UI components,
                  boosting site performance and user experience, driving up the
                  traffic.
                </div>
              </div>
              <div class="timeline_image-wrapper"></div>
            </div>
          </div>
          <div data-w-id="72497fc0-4591-9daf-81b3-b917784e7930" class="timeline_item">
            <div id="h" class="timeline_left">
              <div class="timeline_date-text">Fall 2020</div>
            </div>
            <div id="i" class="timeline_centre">
              <div class="timeline_circle"></div>
            </div>
            <div class="timeline_right">
              <div class="margin-bottom-medium">
                <div class="timeline_text">
                  I kicked off my studies at the University of Toronto, diving
                  into Computer Science, Mathematics, and Statistics. It was
                  here I got the tools and insights that paved the way for my
                  tech adventures ahead.<br />
                </div>
              </div>
              <div class="timeline_image-wrapper">
                <img src="../../public/img/Utoronto_coa.svg.png" loading="lazy" width="480"
                  sizes="(max-width: 479px) 48px, (max-width: 767px) 64px, (max-width: 991px) 36vw, 38vw" alt="" srcset="
                    ../../public/img/Utoronto_coa.svg-p-500.png   500w,
                    ../../public/img/Utoronto_coa.svg-p-800.png   800w,
                    ../../public/img/Utoronto_coa.svg-p-1080.png 1080w,
                    ../../public/img/Utoronto_coa.svg.png        1200w
                  " />
              </div>
            </div>
          </div>
          <div class="overlay-fade-bottom"></div>
          <div class="overlay-fade-top"></div>
        </div>
      </div>
    </div>
    <div data-w-id="a33510ee-228e-eaaa-6baf-5bde8b8e2d5c" class="section-timeline-cta">
      <div class="container">
        <div class="padding-vertical-xlarge">
          <div class="timeline-main_heading-wrapper">
            <div class="margin-bottom-medium">
              <h2>
                <strong>Tracing my steps on this professional journey.</strong>
              </h2>
            </div>
            <p class="paragraph-large">
              From the classroom to industry-leading projects, I started solo,
              fueled by a passion for tech. <br />It kicked off just over four
              years ago... Strap in.
            </p>
          </div>
        </div>
      </div>
    </div>
    <div class="section-footer">
      <div class="background-layer"></div>
      <div class="container">
        <div class="padding-vertical-footer">
          <div class="footer_text-wrapper">
            <div class="margin-bottom-small">
              <h2>Enjoyed my work?</h2>
            </div>
            <div class="margin-bottom-medium">
              <h4>Keep an eye out for more milestones</h4>
            </div>
            <div class="margin-bottom-large">
              <p class="paragraph-large">
                Reach out for career prospects or to provide feedback. Stay
                updated by following me on my featured platforms.
              </p>
            </div>
            <div class="button-wrapper">
              <a href="mailto:roa.brahimi@mail.utoronto.ca"
                class="button-icon-small margin-right-small w-inline-block"><img
                  src="../../public/img/email-icon-white.svg" loading="lazy" alt="" class="button-icon" />
                <div>EMAIL ME</div>
              </a>
              <a href="https://discord.com/users/583305080695029780" target="_blank"
                class="button-icon-small-secondary w-inline-block"><img
                  src="../../public/img/discord-square-color-icon.svg" loading="lazy" alt="" class="button-icon" />
                <div>DISCORD LINK</div>
              </a>
            </div>
          </div>
          <div class="footer_credits-wrapper">
            <p>
              Developed by Roa © 2024 | Relume Figma Kit © 2021
            </p>
          </div>
        </div>
      </div>
    </div>
  </BaseLayout>
</template>

<script>
import BaseLayout from "./BaseLayout.vue";

export default {
  name: "IndexPage",
  components: {
    BaseLayout,
  },
};
</script>

<style scoped>
@import "../../public/styles/timeline.css";
@import "../../public/styles/footer.css";
</style>
