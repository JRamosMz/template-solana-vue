<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <header>
        <nav class="nav">
            <div class="content-nav">
                <div class="nav-logo">
                    <img src="imgs/logo.svg" alt="" class="logo-img">
                    <p class="logo-name">Bonfida</p>
                </div>
                <div class="content-list">
                    <ul class="list-menu">
                        <div class="menuBrowse">
                            <a href="#" class="enlace" onclick="toggleAper()">Browse domains</a>
                            <div class="menu-hidden" id="enlaceBrowse">
                                <a href="#">
                                    <h3>Categories</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </a>
                                <a href="#">
                                    <h3>Listed</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </a>
                                <a href="#">
                                    <h3>Autocioned</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </a>
                                <a href="#">
                                    <h3>Stastics</h3>
                                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                                </a>
                            </div>
                        </div>
                        <a href="#" class="enlace">Learn</a>
                        <a href="#" class="enlace">Build</a>
                        <a href="#" class="enlace">Community</a>
                        <a href="#" class="enlace">Twitter</a>
                    </ul>
                </div>
                <div class="botones">
                    <div class="buscador"><input type="text" class="buscador-letter"><img src="imgs/search.svg" alt="">
                    </div>
                    <hr>
                    <button class="campana"><img src="imgs/campana.svg" alt=""></button>
                    <hr>
                    <div class="content-wallet"><button class="boton-conectWallet">Connect Walltet</button></div>
                    <button class="carrito"><img src="imgs/carrito.svg" alt=""></button>
                </div>
                <div class="pesta??a-campana" >
                    <div class="contenido-pesta??a">
                        <div class="contenido-top">
                            <img src="imgs/campana.svg" alt="" class="campana-ref">
                            <h1>Get notifications</h1>
                            <p>Stay up to date on auctions and offers you receive <br>with Notifi alerts.</p>
                        </div>
                        <div class="contenido-pesta??a-inputs">
                            <div class="textsss">
                                <span>Email</span>
                                <button>Resend Verification email</button>
                            </div>
                            <div class="textsss2">
                                <input type="text" name="" id="" placeholder="Enter email">
                            </div>
                            <div class="or">OR</div>
                            <hr class="divid--">
                        </div>
                        <div class="number">
                            <span class="textsss3">Text message</span>
                            <div class="number-botons-number">
                                <button class="buton-pais">+376</button>
                                <input type="text" placeholder="Enter phone number" class="buton-escrit">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </nav>
    </header>
        <section>
            <div class="entrada">
                <div class="search-entrada">
                    <input type="text" placeholder="Start.sol searching">
                    <hr>
                    <div class="configure-search">
                        <div class="translate">
                            <button class="button-translate">
                                <p>English</p>
                            </button>
                        </div>
                        <button class="button-bulkSearch">
                            <p>Bulk search</p>
                        </button>
                        <div class="boton-lupa">
                            <img src="imgs/search.svg" alt="">
                        </div>
                    </div>
                </div>
                <div class="content-entrada">
                    <div class="izq-content">
                        <div class="content-available_star">
                            <p><img src="imgs/check.svg" alt=""> Available now</p>
                            <div class="star">
                                <img src="imgs/star.svg" alt="">
                            </div>
                        </div>
                        <div class="sirenirk">
                            <h1>Sirenirk.sol</h1>
                            <h3>20 USDC</h3>
                        </div>
                        <button class="add-car">Add to cart</button>
                    </div>
                    <hr class="divid-content_principal">
                    <div class="der-content">
                        <h3>Why get a.sol domain?</h3>
                        <div class="pasos">
                            <div class="pasos-text paso1">
                                <img src="imgs/relampago.png" alt="" class="imgPass">
                                <p>Quickly send and receive funds to a human-readable address</p>
                            </div>
                            <div class="pasos-text paso2">
                                <img src="imgs/layers.png" alt="" class="imgPass">
                                <p>Collect and exchange .sol names directly or as NFTs</p>
                            </div>
                            <div class="pasos-text paso3">
                                <img src="imgs/translate.png" alt="" class="imgPass">
                                <p>Host projects with your unique and exotic domain name</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="content-general_section2">
                <div class="two-div_section">
                    <h1 class="titlesection2">Great alternatives</h1>
                    <div class="options-sections2">
                        <div class="content-butons_Izq">
                            <button class="buton-item">Show All</button>
                            <button class="buton-item">Fixed price resell</button>
                            <button class="buton-item">Auction</button>
                            <button class="buton-item">Unregistered</button>
                        </div>
                        <button class="buton-congigure_Section2">Price range $()+ USD</button>
                        <button class="buton-rays"><img class="buton-rays_img" src="imgs/small.svg" alt=""></button>
                    </div>
                    <div class="grids">
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                        <div class="item1">
                            <div class="star2">
                                <img src="imgs/star.svg" alt="">
                            </div>
                            <h2>sirenirk_40.sol</h2>
                            <div class="comprar-border">
                                <div class="comprar-element">
                                    <div class="precio">
                                        <p class="costo">Price</p>
                                        <div>
                                            <img src="imgs/logo.png" alt="">
                                            <p>20</p>
                                            <small>$20</small>
                                        </div>
                                    </div>
                                    <button class="button-comprar">
                                        <img src="imgs/carrito.svg" alt="">
                                        <h4>Buy it now</h4>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section>
            <div class="content-desenlace">
                <div class="lineal">
                    <div class="boton_center">
                        <h1 class="interrogante_desenlace">Looking for something else?</h1>
                        <div class="borde-boton_center">
                            <button>
                                <p>Browse domains</p>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <footer>
            <div class="pie-bowse">
                <div class="content-lemaAd">
                    <div class="content-info">
                        <div class="nav-logo">
                            <img src="imgs/logo.svg" alt="" class="logo-img">
                            <p class="logo-name">Bonfida</p>
                        </div>
                        <ul class="List-pie">
                            <li>Browse domains</li>
                            <li>Learn</li>
                            <li>Build</li>
                            <li>Community</li>
                            <li>Governance</li>
                        </ul>
                        <div class="redes">
                            <span>Help</span>
                            <img src="imgs/telegram.svg" alt="">
                            <img src="imgs/twitter.svg" alt="">
                            <img src="imgs/discord.svg" alt="">
                        </div>
                    </div>
                    <p class="lema">This web site is hosted on IPFS and is not available in the United States or other
                        prohibited
                        jurisdictions</p>
                </div>
            </div>
        </footer>
</template>
