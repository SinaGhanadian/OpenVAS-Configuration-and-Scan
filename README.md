OpenVAS

Firstly, configure a kali linux virtual machine and Metasploitable 2 virtual machine with an internal network using virtual box.

![Virtual box](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/3da23dd8-83fa-4be6-97a8-b7a5007d2508)

![network](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/6189a9e6-ad1f-4c7e-bba2-9a5f31837b5e)

Install OpenVAS on the Kali machine using the following commands.

![install gvm](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/2c62c3a9-fbdb-4fc8-8ac4-c0e1d9d2951f)

![gvm setup](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/1e3332d6-c0d3-418e-8a98-f24b71d1df71)

![OpenVAS Webpage](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/30eb226a-aac2-4cb0-aeca-feaa6ef30d80)

Inside the Metasploitable 2 machine edit the network interfaces file from dhcp to static ip address.

![Metasploitable network adaptors](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/5ac99bf4-86d9-4d94-a62a-eaea160484b8)

![dhcp](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/7400a22b-eb3b-423b-8517-e7f01b86c1c4)

![Configured](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/e94b55af-09a3-4dec-b9f7-9573827c5768)

Do the exact same for Kali linux.

![kali network 2](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/dc7e76d2-5de6-412b-9303-32f45403c877)

Wait for OpenVAS to update.

![OpenVAS Update](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/50941e11-3158-4f46-885c-a0864f8cecb9)

After update, add the target with the Metasploitable 2 ip address.

![target 2](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/98ac0ac4-c774-4ca0-becf-2f765752d2df)

Scan the target with a full and fast scan with the Metasploitable 2 target.

![OpenVAS Scanner Config](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/cdd4799b-eeca-4280-ae87-638021c09ce6)

![Before Scan](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/c8cffc2e-1e7c-4c55-a879-dd893ced16f4)

Once scan is complete you can view the results.

![Report](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/44e28584-b039-4e43-8bfd-303455e7c6e0)

![Vulnerabilities](https://github.com/SinaGhanadian/OpenVAS-Configuration-and-Scan/assets/15080146/d2cbd1d5-a6c7-44c4-b208-551e77660f68)


