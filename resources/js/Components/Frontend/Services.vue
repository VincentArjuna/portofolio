<script setup>

</script>

<template>
    <section id="services" class="section bg-light-secondary dark:bg-dark-secondary">
        <div class="container mx-auto" v-motion :initial="{ opacity: 0, y: 100, }" :visible="{ opacity: 1, y: 0, }">
            <div class="flex flex-col items-center text-center">
                <h2 class="section-title">What I do for Clients</h2>
                <p class="subtitle">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ultricies arcu quis nisi scelerisque
                    congue. Curabitur rhoncus mauris sit amet dui condimentum pretium.
                </p>
            </div>
            <div class="grid lg:grid-cols-4 gap-8">
                <div class="bg-light-tail-100 dark:bg-dark-navy-500 p-6 rounded-2xl">
                    <div class="text-accent rounded-sm w-12 h-12 flex justify-center items-center mb-24 text-[28px]">
                        <svg class="svg-icon" viewBox="0 0 20 20">
                            <path
                                d="M19.404,6.65l-5.998-5.996c-0.292-0.292-0.765-0.292-1.056,0l-2.22,2.22l-8.311,8.313l-0.003,0.001v0.003l-0.161,0.161c-0.114,0.112-0.187,0.258-0.21,0.417l-1.059,7.051c-0.035,0.233,0.044,0.47,0.21,0.639c0.143,0.14,0.333,0.219,0.528,0.219c0.038,0,0.073-0.003,0.111-0.009l7.054-1.055c0.158-0.025,0.306-0.098,0.417-0.211l8.478-8.476l2.22-2.22C19.695,7.414,19.695,6.941,19.404,6.65z M8.341,16.656l-0.989-0.99l7.258-7.258l0.989,0.99L8.341,16.656z M2.332,15.919l0.411-2.748l4.143,4.143l-2.748,0.41L2.332,15.919z M13.554,7.351L6.296,14.61l-0.849-0.848l7.259-7.258l0.423,0.424L13.554,7.351zM10.658,4.457l0.992,0.99l-7.259,7.258L3.4,11.715L10.658,4.457z M16.656,8.342l-1.517-1.517V6.823h-0.003l-0.951-0.951l-2.471-2.471l1.164-1.164l4.942,4.94L16.656,8.342z">
                            </path>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium mb-2">Web Design</h4>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ultricies arcu quis nisi
                        scelerisque
                        congue. Curabitur rhoncus mauris sit amet dui condimentum pretium. Ut ullamcorper lacus eu
                        fringilla luctus. Duis nec neque feugiat, egestas risus sit amet, tempus lectus. Integer
                        sollicitudin enim tincidunt risus fermentum auctor.
                    </p>
                </div>
                <div class="bg-light-tail-100 dark:bg-dark-navy-500 p-6 rounded-2xl">
                    <div class="text-accent rounded-sm w-12 h-12 flex justify-center items-center mb-24 text-[28px]">
                        <svg class="svg-icon" viewBox="0 0 20 20">
                            <path
                                d="M5.92,11.7c-0.091,0-0.178-0.013-0.265-0.027l-2.433,6.487h5.395l-2.433-6.487C6.097,11.687,6.01,11.7,5.92,11.7z">
                            </path>
                            <path d="M4.254,10.34H0.479l2.11,7.573l2.429-6.477C4.631,11.193,4.348,10.803,4.254,10.34z">
                            </path>
                            <path d="M7.585,10.34c-0.094,0.463-0.378,0.853-0.764,1.096l2.429,6.477l2.019-7.573H7.585z">
                            </path>
                            <path d="M5.018,8.564L2.589,2.087L0.479,9.66h3.775C4.348,9.197,4.631,8.807,5.018,8.564z">
                            </path>
                            <path
                                d="M5.92,8.3c0.091,0,0.178,0.013,0.265,0.027l2.433-6.487H3.222l2.433,6.487C5.742,8.313,5.829,8.3,5.92,8.3z">
                            </path>
                            <path d="M7.585,9.66h3.684L9.25,2.087L6.821,8.564C7.208,8.807,7.491,9.197,7.585,9.66z">
                            </path>
                            <circle cx="5.92" cy="10" r="0.68"></circle>
                            <path
                                d="M11.763,8.872L12.064,10l-0.301,1.128c0.184,0.101,0.392,0.164,0.617,0.164c0.712,0,1.292-0.58,1.292-1.292s-0.58-1.292-1.292-1.292C12.156,8.708,11.947,8.771,11.763,8.872z">
                            </path>
                            <path
                                d="M12.55,8.368c0,0.007-0.006,0.01-0.007,0.017c0.327,0.033,0.623,0.16,0.864,0.357c0.004-0.005,0.002-0.011,0.007-0.016l0.637-0.637c-0.408-0.357-0.927-0.583-1.501-0.622V8.368z">
                            </path>
                            <path
                                d="M11.438,7.652l0.236,0.887c0.168-0.08,0.35-0.135,0.543-0.155c-0.001-0.006-0.007-0.01-0.007-0.017V7.467C11.938,7.485,11.681,7.555,11.438,7.652z">
                            </path>
                            <path
                                d="M12.21,12.533v-0.901c0-0.007,0.006-0.01,0.007-0.017c-0.193-0.019-0.375-0.075-0.543-0.155l-0.236,0.887C11.681,12.445,11.938,12.515,12.21,12.533z">
                            </path>
                            <path
                                d="M14.913,10.17h-0.901c-0.007,0-0.01-0.006-0.017-0.007c-0.033,0.327-0.16,0.623-0.357,0.864c0.005,0.004,0.011,0.002,0.016,0.007l0.637,0.637C14.649,11.263,14.875,10.744,14.913,10.17z">
                            </path>
                            <path
                                d="M14.291,8.329l-0.637,0.637c-0.004,0.004-0.011,0.003-0.016,0.007c0.197,0.241,0.324,0.537,0.357,0.864c0.006-0.001,0.01-0.007,0.017-0.007h0.901C14.875,9.256,14.649,8.737,14.291,8.329z">
                            </path>
                            <path
                                d="M14.051,11.911l-0.637-0.637c-0.004-0.004-0.003-0.011-0.007-0.016c-0.241,0.197-0.537,0.324-0.864,0.357c0.001,0.006,0.007,0.01,0.007,0.017v0.901C13.124,12.494,13.643,12.268,14.051,11.911z">
                            </path>
                            <path
                                d="M17.345,1.839h-6.529L10.352,3.58l0.624,2.34h1.064c2.285,0,4.08,1.882,4.08,4.08v0c0,2.254-1.827,4.08-4.08,4.08h-1.064l-0.624,2.34l0.464,1.741h6.529L19.521,10L17.345,1.839z">
                            </path>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium mb-2">Web Development</h4>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ultricies arcu quis nisi
                        scelerisque
                        congue. Curabitur rhoncus mauris sit amet dui condimentum pretium. Ut ullamcorper lacus eu
                        fringilla luctus. Duis nec neque feugiat, egestas risus sit amet, tempus lectus. Integer
                        sollicitudin enim tincidunt risus fermentum auctor.
                    </p>
                </div>
                <div class="bg-light-tail-100 dark:bg-dark-navy-500 p-6 rounded-2xl">
                    <div class="text-accent rounded-sm w-12 h-12 flex justify-center items-center mb-24 text-[28px]">
                        <svg class="svg-icon" viewBox="0 0 20 20" enable-background="new 0 0 20 20"
                            xml:space="preserve">
                            <circle cx="3.274" cy="6.198" r="0.585"></circle>
                            <rect x="6.198" y="4.736" width="0.585" height="2.34"></rect>
                            <path
                                d="M15.849,11.669v-1.064l-1.072-0.715l-0.829,1.659c-0.428,0.174-0.73,0.592-0.73,1.083c0,0.265,0.091,0.507,0.24,0.703l-0.201,2.806h1.759l0.191-2.676c0.216-0.212,0.35-0.507,0.35-0.833c0-0.102-0.017-0.2-0.042-0.294L15.849,11.669z M14.387,13.217c-0.322,0-0.585-0.262-0.585-0.585c0-0.322,0.262-0.585,0.585-0.585c0.322,0,0.585,0.262,0.585,0.585C14.971,12.954,14.709,13.217,14.387,13.217z">
                            </path>
                            <polygon
                                points="15.721,7.368 19.066,7.368 19.066,3.859 16.141,2.894 15.556,2.104 11.462,2.104 10.877,2.894 8.538,3.859 8.538,7.368 11.297,7.368 	">
                            </polygon>
                            <path
                                d="M5.029,7.368h0.585V4.444h-2.34l-1.755,1.17v0.877H0.496c-0.081,0-0.146,0.065-0.146,0.146s0.065,0.146,0.146,0.146h1.024v0.585H0.642C0.48,7.368,0.35,7.499,0.35,7.66S0.48,7.953,0.642,7.953h3.802L5.029,7.368zM3.274,7.076c-0.485,0-0.877-0.393-0.877-0.877s0.393-0.877,0.877-0.877s0.877,0.393,0.877,0.877S3.758,7.076,3.274,7.076z">
                            </path>
                            <path
                                d="M18.96,16.141l-0.631-2.944c0.094-0.168,0.151-0.359,0.151-0.565c0-0.295-0.113-0.561-0.292-0.766v-1.427l0.71-2.486H9.708c-0.646,0-1.17,0.524-1.17,1.17c0,0.162,0.033,0.317,0.093,0.457l-0.682,2.047c-0.346,0.203-0.58,0.575-0.58,1.005c0,0.152,0.031,0.297,0.084,0.431l-1.099,3.079h1.863l0.407-1.141l1.504,0.725l0.761-1.581l-1.51-0.711c0.201-0.209,0.33-0.488,0.33-0.801c0-0.162-0.033-0.316-0.093-0.457l0.556-1.668l1.73-1.384h2.778l1.755,1.17v1.48v0.093c-0.18,0.206-0.292,0.472-0.292,0.766c0,0.392,0.195,0.738,0.492,0.95l0.536,2.559H18.96z M8.538,13.217c-0.322,0-0.585-0.262-0.585-0.585c0-0.322,0.262-0.585,0.585-0.585c0.322,0,0.585,0.262,0.585,0.585C9.123,12.954,8.86,13.217,8.538,13.217z M9.708,9.708c-0.322,0-0.585-0.262-0.585-0.585c0-0.322,0.262-0.585,0.585-0.585c0.322,0,0.585,0.262,0.585,0.585C10.292,9.445,10.03,9.708,9.708,9.708z M17.311,8.538c0.322,0,0.585,0.262,0.585,0.585c0,0.322-0.262,0.585-0.585,0.585s-0.585-0.262-0.585-0.585C16.726,8.8,16.988,8.538,17.311,8.538z M16.726,12.632c0-0.322,0.262-0.585,0.585-0.585s0.585,0.262,0.585,0.585c0,0.322-0.262,0.585-0.585,0.585S16.726,12.954,16.726,12.632z">
                            </path>
                            <rect x="7.368" y="4.736" width="0.585" height="2.34"></rect>
                            <polygon
                                points="11.89,14.086 11.468,14.288 10.517,16.265 10.622,16.721 11.413,17.101 12.68,14.466 	">
                            </polygon>
                            <polygon
                                points="19.285,16.726 17.092,16.726 16.726,17.019 16.726,17.896 19.65,17.896 19.65,17.019 	">
                            </polygon>
                            <polygon
                                points="12.997,16.726 12.632,17.019 12.632,17.896 15.556,17.896 15.556,17.019 15.191,16.726 	">
                            </polygon>
                            <polygon
                                points="5.979,16.726 5.613,17.019 5.613,17.896 8.538,17.896 8.538,17.019 8.172,16.726 	">
                            </polygon>
                            <path
                                d="M5.933,13.752l0.558,0.263l0.344-0.963c-0.035-0.138-0.052-0.278-0.052-0.419c0-0.536,0.253-1.044,0.672-1.375l0.634-1.903l-2.461,2.109c-0.005,0-0.01-0.002-0.015-0.002c-0.646,0-1.17,0.524-1.17,1.17c0,0.646,0.524,1.17,1.17,1.17C5.725,13.802,5.831,13.781,5.933,13.752z M5.029,12.632c0-0.322,0.262-0.585,0.585-0.585s0.585,0.262,0.585,0.585c0,0.322-0.262,0.585-0.585,0.585S5.029,12.954,5.029,12.632z">
                            </path>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium mb-2">Branding</h4>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ultricies arcu quis nisi
                        scelerisque
                        congue. Curabitur rhoncus mauris sit amet dui condimentum pretium. Ut ullamcorper lacus eu
                        fringilla luctus. Duis nec neque feugiat, egestas risus sit amet, tempus lectus. Integer
                        sollicitudin enim tincidunt risus fermentum auctor.
                    </p>
                </div>
                <div class="bg-light-tail-100 dark:bg-dark-navy-500 p-6 rounded-2xl">
                    <div class="text-accent rounded-sm w-12 h-12 flex justify-center items-center mb-24 text-[28px]">
                        <svg class="svg-icon" viewBox="0 0 20 20">
                            <path d="M19.129,18.164l-4.518-4.52c1.152-1.373,1.852-3.143,1.852-5.077c0-4.361-3.535-7.896-7.896-7.896
								c-4.361,0-7.896,3.535-7.896,7.896s3.535,7.896,7.896,7.896c1.934,0,3.705-0.698,5.078-1.853l4.52,4.519
								c0.266,0.268,0.699,0.268,0.965,0C19.396,18.863,19.396,18.431,19.129,18.164z M8.567,15.028c-3.568,0-6.461-2.893-6.461-6.461
								s2.893-6.461,6.461-6.461c3.568,0,6.46,2.893,6.46,6.461S12.135,15.028,8.567,15.028z"></path>
                        </svg>
                    </div>
                    <h4 class="text-xl font-medium mb-2">SEO</h4>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam ultricies arcu quis nisi
                        scelerisque
                        congue. Curabitur rhoncus mauris sit amet dui condimentum pretium. Ut ullamcorper lacus eu
                        fringilla luctus. Duis nec neque feugiat, egestas risus sit amet, tempus lectus. Integer
                        sollicitudin enim tincidunt risus fermentum auctor.
                    </p>
                </div>
            </div>
        </div>
    </section>
</template>