<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-3  text-white">La mejor forma de regresar a clases!
                                    <span>Froggy Store - Libreria y variedades</span>
                                </h1>
                                <p class="lead  text-white">Busca en nuestro catalogo escolar, donde podras encontrar utiles, mochilas, y mucho mas!</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                                class="mb-3 mb-sm-0"
                                                type="info"
                                                icon="fa fa-code">
                                        Catalogo escolar
                                    </base-button>
                                    <base-button tag="a"
                                                href="https://wa.me/50377887721"
                                                class="mb-3 mb-sm-0"
                                                type="white"
                                                icon="ni ni-chat-round"
                                                target="_blank">
                                        Crea tu cotización
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Compra</h6>
                                    <p class="description mt-3">Los mejores productos con la mejor atencion, con los mejores
                                        precios.
                                    </p>
                                    <div>
                                        <badge type="primary" rounded>#compras</badge>
                                        <badge type="primary" rounded>#ventas</badge>
                                        <badge type="primary" rounded>#froggystore</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Leer Más
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">Lleva</h6>
                                    <p class="description mt-3">Lleva los mejores productos al mejor precio solo en tu tienda
                                        Froggy Store.</p>
                                    <div>
                                        <badge type="success" rounded>#pide</badge>
                                        <badge type="success" rounded>#paga</badge>
                                        <badge type="success" rounded>#disfruta</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Catalogos
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">Disfruta</h6>
                                    <p class="description mt-3">Pide a domicilio, siempre las mejores cosas</p>
                                    <div>
                                        <badge type="warning" rounded>marketing</badge>
                                        <badge type="warning" rounded>product</badge>
                                        <badge type="warning" rounded>launch</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Contactar
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section bg-secondary">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6">
                        <div class="card bg-default shadow border-0">
                            <img v-lazy="'img/theme/img-1-1200x1000.jpg'" class="card-img-top">
                            <blockquote class="card-blockquote">
                                <svg preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 583 95"
                                        class="svg-bg">
                                    <polygon points="0,52 583,95 0,95" class="fill-default"></polygon>
                                    <polygon points="0,42 583,95 683,0 0,95" opacity=".2" class="fill-default"></polygon>
                                </svg>
                                <h4 class="display-3 font-weight-bold text-white">Nuestro objetivo</h4>
                                <p class="lead text-italic text-white">Nuestro objetivo es que obtengas los mejores precios y mejores cotizaciones
                                    con nuestros agentes especializados.
                                </p>
                            </blockquote>
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="pl-md-5">
                            <icon name="ni ni-settings" class="mb-5" size="lg" type="warning" shadow rounded></icon>

                            <h3>Ven a Froggy Store!</h3>
                            <p class="lead">Estamos ubicados en residencial bosques de la paz, calle 11 poniente casa 40</p>
                            <p>Siempre dispuestos a darte la mejor atencion y los mejores productos para tu año escolar.</p>
                            <p>¿Que esperas? Agenda hoy una llamada con uno de nuestros agentes de venta especializados</p>
                            <a href="#" class="font-weight-bold text-warning mt-5">Agendar</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-1 bg-gradient-warning shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container py-0">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-lg-2 ml-lg-auto">
                        <div class="position-relative pl-md-5">
                            <img src="img/ill/ill-2.svg" class="img-center img-fluid">
                        </div>
                    </div>
                    <div class="col-lg-6 order-lg-1">
                        <div class="d-flex px-3">
                            <div>
                                <icon name="ni ni-building" size="lg" class="bg-gradient-white" color="primary" shadow
                                        rounded></icon>
                            </div>
                            <div class="pl-4">
                                <h4 class="display-3 text-white">Para una interfaz moderna</h4>
                                <p class="text-white">Tenemos catalogos de productos modernos como:</p>
                            </div>
                        </div>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-satisfied" gradient="success" color="white" shadow
                                            rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-success">Productos Gaming</h5>
                                    <li>Audifonos bluetooth</li>
                                    <li>Smart Watch</li>
                                    <li>bocinas bluetooth</li>
                                    <li>Guias led bluetooth</li>
                                    <br>
                                    <a href="#" class="text-success">Cotizar</a>
                                </div>
                            </div>
                        </card>
                        <card shadow class="shadow-lg--hover mt-5">
                            <div class="d-flex px-3">
                                <div>
                                    <icon name="ni ni-active-40" gradient="warning" color="white" shadow
                                            rounded></icon>
                                </div>
                                <div class="pl-4">
                                    <h5 class="title text-warning">Productos para el hogar</h5>
                                    <h5 class="title text-success">Productos Gaming</h5>
                                    <li>Cogines</li>
                                    <li>Trapeadores giratorios</li>
                                    <li>estuches inteligentes</li>
                                    <li>Cubiertos</li>
                                    <br>
                                    <a href="#" class="text-success">Cotizar</a>
                                </div>
                            </div>
                        </card>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row justify-content-center text-center mb-lg">
                    <div class="col-lg-8">
                        <h2 class="display-3">Nuestro equipamiento</h2>
                        <p class="lead text-muted">Empresa familiar</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                        <h2 class="display-3 text-white">Venta de globos con helio</h2>
                        <p class="lead text-white">Para todas las ocaciones y materiales para decoracion y fiestas.</p>
                    </div>
                </div>
                <div class="row row-grid mt-5">
                    <div class="col-lg-4">
                        <icon name="ni ni-settings" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Servicio de decoracion</h5>
                        <p class="text-white mt-3">Contamos con un equipo especializado para decoracioines de eventos</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-ruler-pencil" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Surtimos listas completas de estudiantes</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                    <div class="col-lg-4">
                        <icon name="ni ni-atom" size="lg" gradient="white" shadow round color="primary"></icon>
                        <h5 class="text-white mt-3">Implementos para entornos empresariales</h5>
                        <p class="text-white mt-3">Some quick example text to build on the card title and make up the
                            bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Como contactarnos ?</h4>
                            <p class="mt-0">Por que tú eres importante para nosotros, llena el formulario, y nosotros te contactaremos!</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Tu nombre"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                                cols="80" placeholder="Mensaje"></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Enviar mensaje
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script>
    export default {
        name: "home",
        components: {}
    };
</script>
