# Lanza Personas · Lab 16 (UIKit Dynamics)

| Criterio de la rúbrica | Dónde está en ViewController.swift |
|---|---|
| Animaciones UIView spring y keyframes | `showOverlay` (spring + keyframes del título), `loadNextProjectile` (spring), `floatingText`, `shakeWorld`, `applyDamage` (keyframes) |
| UIDynamicAnimator, límites de colisión, propiedades físicas | `setupPhysics` (animator, boundary "ground"), `addBody` (density, elasticity, friction, resistance, angularResistance), `BallView`-like con `collisionBoundsType = .ellipse` en `ProjectileView` y `RivalView` |
| UICollisionBehaviorDelegate, gravedad y push | `collisionBehavior(...beganContactFor...)` (item-item y límite), `gravity` (UIGravityBehavior), `impulse` (UIPushBehavior para lanzar y para los poderes), `spawnDebris` (push + gravedad en los restos) |
| Observaciones y conclusiones críticas | Escríbelas tú en el informe: prueba cambiar `speedFactor`, `gravity.magnitude`, densidades de los materiales, elasticity de los proyectiles y anota qué pasa. |

Extras: fotos propias como proyectiles, 3 niveles, 4 tipos de proyectil con poderes,
3 materiales con vida distinta, trayectoria punteada, partículas, estrellas, récord (UserDefaults),
vibración háptica, nubes animadas y menú.

Cambiar las fotos: copia PNG a LanzaPersonas/Personas/ con nombre persona_1.png, persona_2.png...
