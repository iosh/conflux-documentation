---
sidebar_position: 1
title: '¿Qué es Conflux?'
---

Conflux se destaca como una blockchain pública con un rendimiento superior, un mecanismo de consenso único y un innovador diseño dual-space. Estas características permiten que Conflux ofrezca una plataforma rápida, segura y descentralizada que es adecuada para diversas aplicaciones, incluidas las finanzas descentralizadas y los juegos.

Conflux utiliza un [mecanismo de consenso](./consensus-mechanisms/consensus-mechanisms.md) híbrido, combinando Prueba de Trabajo (PoW) y Prueba de Participación (PoS), garantizando alta seguridad, rendimiento y descentralización. El consenso PoW de Conflux aprovecha la estructura [ Tree-Graph](./consensus-mechanisms/proof-of-work/tree-graph.md) y el [algoritmo GHAST](./consensus-mechanisms/proof-of-work/ghast.md), ofreciendo un alto rendimiento de hasta 3,000 TPS y una latencia de confirmación de 1 minuto, manteniendo el mismo nivel de descentralización que Bitcoin y Ethereum. El consenso PoS de Conflux ofrece la finalidad de la red, mitigando el riesgo de un [ataque del 51%](./consensus-mechanisms/proof-of-stake/why-pos.md).  En consecuencia, Conflux tiene la capacidad de manejar eficientemente un gran número de transacciones, convirtiéndola en una plataforma robusta y fiable para una amplia gama de aplicaciones.

La red Conflux comprende dos distintos [espacios](./spaces.md): Conflux [Core Space](../../core/core.mdx) y Conflux [eSpace](../../espace/learn/overview.md). El Core Space es la red blockchain principal que utiliza el mecanismo de consenso híbrido y cuenta con un [mecanismo de subsidio de gas](../../core/learn/core-space-basics/internal-contracts/sponsor-whitelist-control.md). El mecanismo de subsidio permite a los usuarios del proyecto interactuar con contratos sin tener un saldo, reduciendo el límite de uso de la blockchain y expandiendo la base de usuarios. El eSpace es totalmente compatible con la máquina virtual de Ethereum (EVM), que permite a los desarrolladores migrar fácilmente sus contratos inteligentes de Ethereum a Conflux eSpace y beneficiarse de su alto rendimiento y escalabilidad. Conflux Core Space y eSpace pueden comunicarse entre sí a través del contrato [CrossSpaceCall](../../core/learn/core-space-basics/internal-contracts/crossSpaceCall.md), que facilita la transferencia atómica de fondos y la ejecución atómica de llamadas de contratos inteligentes entre los dos espacios.

:::tip

Bienvenidos al sitio de documentación de Conflux, su punto de partida para aprender sobre los conceptos básicos y el desarrollo de Conflux. ¡Disfrute la visita!

:::