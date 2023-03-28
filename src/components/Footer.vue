<template>
    <footer class="footer">
        <div class="footer-body container">
           

            <div class="row justify-content-between align-items-start">
                <div class="col-xs-12 col-lg-3">
                    <a class="navbar-brand mb-2" href="#">
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
                                <linearGradient x1="14.2479105%" y1="0%" x2="68.77279%" y2="111.597742%"
                                    id="linearGradient-1">
                                    <stop stop-color="#FF0000" offset="0.0863882212%"></stop>
                                    <stop stop-color="#FF0033" offset="100%"></stop>
                                </linearGradient>
                                <linearGradient x1="82.8606725%" y1="0%" x2="31.5206006%" y2="107.068238%"
                                    id="linearGradient-2">
                                    <stop stop-color="#00FF99" offset="0%"></stop>
                                    <stop stop-color="#00FF55" offset="100%"></stop>
                                </linearGradient>
                            </defs>
                        </svg>
                    </a>
                    <p class="footer-info-text">
                        PulseX, the leading DEX on PulseChain with the best farms in DeFi.
                    </p>
                    <div class="footer-social-icons">
                        <a href="#" rel="noreferrer" target="_blank" class="footer-social-icon" title="Github">
                            <div class="footer-social-icon-container">
                                <i class="bi bi-github"></i>
                            </div>
                        </a>
                        <a href="#" rel="noreferrer" target="_blank" class="footer-social-icon ms-3" title="Telegram" >
                            <div class="footer-social-icon-container">
                                <i class="bi bi-telegram"></i>
                            </div>
                        </a>
                    </div>
                </div>

                <div class="col-xs-12 col-md-4 col-lg-2 footer-list">
                    <h3>PulseX</h3>
                    <ul>
                        <li>
                            <a href="#" rel="noreferrer" class="footer-link" target="_blank">Submit an Issue</a>
                        </li>
                        <li>
                            <a href="#" rel="noreferrer" class="footer-link">Contribute</a>
                        </li>
                        <li>
                            <a href="#" rel="noreferrer" class="footer-link">Telegram</a>
                        </li>

                        <input id="js-coin-name" class="d-none" value="tPLS" />

                        <input id="js-subnetwork" class="d-none" value="Testnet v3" />
                        <li>
                            <a class="footer-link js-btn-add-chain-to-mm btn-add-chain-to-mm in-footer"
                                style="cursor: pointer" href="/connect">
                                Add Testnet v3
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="col-xs-12 col-md-4 col-lg-2 footer-list">
                    <h3>Test Networks</h3>
                    <ul>
                        <li>
                            <a href="#" rel="noreferrer" class="footer-link">
                                Testnet v2b
                            </a>
                        </li>
                    </ul>
                </div>

                <div class="col-xs-12 col-md-4 col-lg-2 footer-list">
                    <h3>Other Explorers</h3>
                    <ul>
                        <li>
                            <a href="#" rel="noreferrer" class="footer-link">
                                Testnet v3 Beacon
                            </a>
                        </li>
                    </ul>
                </div>
            </div>

            <div>
                Version:
                <a href="#" class="footer-link" target="_blank">v5.1.1-beta</a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: "Footer",
    methods: {

    }
};
</script>