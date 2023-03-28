<template>
  <header class="main-header">
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <span class="navbar-brand-font">Pulse</span>
          <svg viewBox="0 0 551 655" width="24px" color="text" xmlns="http://www.w3.org/2000/svg"
            class="sc-bdvvtL juDOJv">
            <g id="Artboard" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
              <g id="Group-4-Copy-4">
                <path
                  d="M350.607,412.346 L471,622 L334.596159,622 C325.647006,622 317.380432,617.21648 312.921058,609.457529 L312.921058,609.457529 L274.985,543.451 L350.607,412.346 Z M136.67325,65 C145.625727,65 153.894842,69.7870435 158.352984,77.550536 L158.352984,77.550536 L236.655,213.908 L160.983,345.098 L0,65 Z"
                  id="Combined-Shape-Copy" fill="url(#linearGradient-1)"></path>
                <path
                  d="M186.068261,630.060049 L551,0 L551,0 L427.299604,0 C409.442016,-3.2246751e-14 392.940022,9.52392606 384.006301,24.9862061 L20,655 L20,655 L142.801715,655 C160.640215,655 177.127587,645.496254 186.068261,630.060049 Z"
                  id="Path-4-Copy-2" fill="url(#linearGradient-2)"></path>
              </g>
            </g>
            <defs>
              <linearGradient x1="14.2479105%" y1="0%" x2="68.77279%" y2="111.597742%" id="linearGradient-1">
                <stop stop-color="#FF0000" offset="0.0863882212%"></stop>
                <stop stop-color="#FF0033" offset="100%"></stop>
              </linearGradient>
              <linearGradient x1="82.8606725%" y1="0%" x2="31.5206006%" y2="107.068238%" id="linearGradient-2">
                <stop stop-color="#00FF99" offset="0%"></stop>
                <stop stop-color="#00FF55" offset="100%"></stop>
              </linearGradient>
            </defs>
          </svg>
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
          aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <i class="bi bi-list fs-4 text-white"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item dropdown">
              <a class="nav-link active dropdown-toggle" role="button" data-bs-toggle="dropdown" aria-expanded="false"
                href="#">Trade</a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item active fw-bold text-white" href="#">Exchange</a></li>
                <li><a class="dropdown-item" href="#liquidity">Liquidity</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                aria-expanded="false">Earn</a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Farms</a></li>
                <li><a class="dropdown-item" href="#">Pools</a></li>
                <!-- <li><a class="dropdown-item" href="#">Telegram</a></li> -->
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                <i class="bi bi-three-dots"></i>
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Info</a></li>
                <li><a class="dropdown-item" href="#">Twitter</a></li>
                <li><a class="dropdown-item" href="#">Telegram</a></li>
              </ul>
            </li>
          </ul>
          <div class="navbar-nav mmm ms-auto align-items-center">
            <a href="#" class="nav-link">
              <svg viewBox="0 0 551 655" width="24px" color="text" xmlns="http://www.w3.org/2000/svg"
                class="sc-bdvvtL juDOJv">
                <g id="Artboard" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd">
                  <g id="Group-4-Copy-4">
                    <path
                      d="M350.607,412.346 L471,622 L334.596159,622 C325.647006,622 317.380432,617.21648 312.921058,609.457529 L312.921058,609.457529 L274.985,543.451 L350.607,412.346 Z M136.67325,65 C145.625727,65 153.894842,69.7870435 158.352984,77.550536 L158.352984,77.550536 L236.655,213.908 L160.983,345.098 L0,65 Z"
                      id="Combined-Shape-Copy" fill="url(#linearGradient-1)"></path>
                    <path
                      d="M186.068261,630.060049 L551,0 L551,0 L427.299604,0 C409.442016,-3.2246751e-14 392.940022,9.52392606 384.006301,24.9862061 L20,655 L20,655 L142.801715,655 C160.640215,655 177.127587,645.496254 186.068261,630.060049 Z"
                      id="Path-4-Copy-2" fill="url(#linearGradient-2)"></path>
                  </g>
                </g>
                <defs>
                  <linearGradient x1="14.2479105%" y1="0%" x2="68.77279%" y2="111.597742%" id="linearGradient-1">
                    <stop stop-color="#FF0000" offset="0.0863882212%"></stop>
                    <stop stop-color="#FF0033" offset="100%"></stop>
                  </linearGradient>
                  <linearGradient x1="82.8606725%" y1="0%" x2="31.5206006%" y2="107.068238%" id="linearGradient-2">
                    <stop stop-color="#00FF99" offset="0%"></stop>
                    <stop stop-color="#00FF55" offset="100%"></stop>
                  </linearGradient>
                </defs>
              </svg>
              <span class="fw-bold">$0.00000</span>
            </a>
            <a href="#" class="nav-link ms-2"><i class="bi bi-globe"></i></a>
            <a href="#" data-bs-toggle="modal" data-bs-target="#exampleModal" class="nav-link ms-2"><i
                class="bi bi-gear"></i></a>
            <a href="/connect" class="btn btn-primary_theme">Connect Wallet</a>
          </div>
        </div>
      </div>
    </nav>
  </header>

  <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm ">
      <div class="modal-content etAOfZ">
        <div class="modal-header gpgsbt">
          <h1 class="modal-title fs-6" id="exampleModalLabel">Settings</h1>
          <button type="button" class="bg-transparent fs-6 border-0 eSnqot" data-bs-dismiss="modal" aria-label="Close">
            <i class="bi bi-x fs-5 fw-4"></i>
          </button>
        </div>
        <div class="modal-body">
          <div class="sc-jRQBWg sc-gKclnd sc-edERGn gREMsN hrZfTH ijEEBQ">
            <div class="sc-jRQBWg sc-gKclnd iRMqpN kNfYKT">
              <div font-size="12px" color="secondary" class="sc-gsDKAQ iZMpIw">Global</div>
              <div class="sc-jRQBWg sc-gKclnd gREMsN kNfYKT">
                <div class="sc-jRQBWg sc-gKclnd eIFiob hxGduz">
                  <div color="text" class="sc-gsDKAQ bzOYlz">Default Transaction Speed (GWEI)</div>
                  <div class="sc-jRQBWg bIreVU">
                    <div class="sc-jvvksu fArJAz"><svg viewBox="0 0 24 24" color="textSubtle" width="16px"
                        xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                        <path
                          d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                        </path>
                      </svg></div>
                  </div>
                </div>
                <div class="sc-jRQBWg sc-gKclnd gREMsN jbqGyo"><button class="sc-hKwDye hEwApd" scale="sm">Standard
                    (2)</button><button class="sc-hKwDye hEwApd" scale="sm">Fast (3)</button><button
                    class="sc-hKwDye xSuXk" scale="sm">Instant (4)</button></div>
              </div>
            </div>
            <div class="sc-jRQBWg sc-gKclnd jZNWJz kNfYKT">
              <div font-size="12px" color="secondary" class="sc-gsDKAQ iZMpIw">Swaps &amp; Liquidity</div>
              <div class="sc-jRQBWg sc-gKclnd gREMsN kNfYKT">
                <div class="sc-jRQBWg sc-gKclnd jbvNDO kNfYKT">
                  <div class="sc-jRQBWg sc-gKclnd eIFiob hrZfTH">
                    <div color="text" class="sc-gsDKAQ bzOYlz">Slippage Tolerance</div>
                    <div class="sc-jRQBWg bIreVU">
                      <div class="sc-jvvksu fArJAz"><svg viewBox="0 0 24 24" color="textSubtle" width="16px"
                          xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                          <path
                            d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                          </path>
                        </svg></div>
                    </div>
                  </div>
                  <div class="sc-jRQBWg sc-gKclnd gREMsN jbqGyo"><button class="sc-hKwDye hEwApd"
                      scale="sm">0.1%</button><button class="sc-hKwDye iKhWtI" scale="sm">0.5%</button><button
                      class="sc-hKwDye kLeQhJ" scale="sm">1.0%</button>
                    <div class="sc-jRQBWg sc-gKclnd gREMsN hxGduz">
                      <div width="76px" class="sc-jRQBWg cQDEbq"><input scale="sm" inputmode="decimal"
                          pattern="^[0-9]*[.,]?[0-9]{0,2}$" placeholder="0.50" class="sc-iqseJM fHYnJI" value=""></div>
                      <div color="primary" class="sc-gsDKAQ iKqmMy">%</div>
                    </div>
                  </div>
                </div>
                <div class="sc-jRQBWg sc-gKclnd jbvNDO jemUpf">
                  <div class="sc-jRQBWg sc-gKclnd gREMsN hxGduz">
                    <div color="text" class="sc-gsDKAQ bzOYlz">Tx deadline (mins)</div>
                    <div class="sc-jRQBWg bIreVU">
                      <div class="sc-jvvksu fArJAz"><svg viewBox="0 0 24 24" color="textSubtle" width="16px"
                          xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                          <path
                            d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                          </path>
                        </svg></div>
                    </div>
                  </div>
                  <div class="sc-jRQBWg sc-gKclnd gREMsN hrZfTH">
                    <div width="52px" class="sc-jRQBWg kkUceY"><input scale="sm" inputmode="numeric" pattern="^[0-9]+$"
                        placeholder="20" class="sc-iqseJM fHYnJI" value=""></div>
                  </div>
                </div>
              </div>
            </div>
            <div class="sc-jRQBWg sc-gKclnd jbvNDO jemUpf">
              <div class="sc-jRQBWg sc-gKclnd gREMsN hxGduz">
                <div color="text" class="sc-gsDKAQ bzOYlz">Expert Mode</div>
                <div class="sc-jRQBWg bIreVU">
                  <div class="sc-jvvksu fArJAz"><svg viewBox="0 0 24 24" color="textSubtle" width="16px"
                      xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                      <path
                        d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                      </path>
                    </svg></div>
                </div>
              </div>
              <div scale="md" class="sc-XxNYO fFqWbB"><input scale="md" id="toggle-expert-mode-button" type="checkbox"
                  class="sc-dkYRCH dtuemF">
                <div scale="md" class="sc-dtDOqo fErgxj"></div>
              </div>
            </div>
            <div class="sc-jRQBWg sc-gKclnd jbvNDO jemUpf">
              <div class="sc-jRQBWg sc-gKclnd gREMsN hxGduz">
                <div color="text" class="sc-gsDKAQ bzOYlz">Disable Multihops</div>
                <div class="sc-jRQBWg bIreVU">
                  <div class="sc-jvvksu fArJAz"><svg viewBox="0 0 24 24" color="textSubtle" width="16px"
                      xmlns="http://www.w3.org/2000/svg" class="sc-bdvvtL hbIeON">
                      <path
                        d="M12 2C6.48 2 2 6.48 2 12C2 17.52 6.48 22 12 22C17.52 22 22 17.52 22 12C22 6.48 17.52 2 12 2ZM12 20C7.59 20 4 16.41 4 12C4 7.59 7.59 4 12 4C16.41 4 20 7.59 20 12C20 16.41 16.41 20 12 20ZM11 16H13V18H11V16ZM12.61 6.04C10.55 5.74 8.73 7.01 8.18 8.83C8 9.41 8.44 10 9.05 10H9.25C9.66 10 9.99 9.71 10.13 9.33C10.45 8.44 11.4 7.83 12.43 8.05C13.38 8.25 14.08 9.18 14 10.15C13.9 11.49 12.38 11.78 11.55 13.03C11.55 13.04 11.54 13.04 11.54 13.05C11.53 13.07 11.52 13.08 11.51 13.1C11.42 13.25 11.33 13.42 11.26 13.6C11.25 13.63 11.23 13.65 11.22 13.68C11.21 13.7 11.21 13.72 11.2 13.75C11.08 14.09 11 14.5 11 15H13C13 14.58 13.11 14.23 13.28 13.93C13.3 13.9 13.31 13.87 13.33 13.84C13.41 13.7 13.51 13.57 13.61 13.45C13.62 13.44 13.63 13.42 13.64 13.41C13.74 13.29 13.85 13.18 13.97 13.07C14.93 12.16 16.23 11.42 15.96 9.51C15.72 7.77 14.35 6.3 12.61 6.04Z">
                      </path>
                    </svg></div>
                </div>
              </div>
              <div scale="md" class="sc-XxNYO fFqWbB">
                <input scale="md" id="toggle-disable-multihop-button" type="checkbox" class="sc-dkYRCH dtuemF">
                <div scale="md" class="sc-dtDOqo fErgxj"></div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  methods: {
    getImgUrl(pic) {
      var images = require.context("../assets/img");
      return images("./" + pic.toLowerCase());
    }
  }
};
</script>

