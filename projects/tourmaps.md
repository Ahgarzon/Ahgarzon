# TourMaps — AI and mobile integration

**Collaborative project · Pilot · Integration case study**

[Profile](../README.md) · [Directory](../PROJECTS.md) · [Public APK repository](https://github.com/Ahgarzon/tm-apk)

## Context

TourMaps is a preexisting tourism application created by James. My work is the AI and mobile integration around that product. This distinction matters: the underlying application and its existing audience are not solely my work.

## My contribution

I work on the conversational-assistance experience, mobile integration and supporting services, including the pilot's testing and release documentation.

## TourCauca and regional tourism

My [public portfolio](https://angelszs.site/?enfoque=negocio) also documents my participation in the conceptual and technological structuring of **TourCauca**, a regional tourism initiative recognized by Colombia's Congress. This is a contribution to a collaborative initiative; the recognition is attributed to the initiative.

## Integration view

```mermaid
flowchart LR
    A[Existing TourMaps product] <--> B[Mobile integration]
    B <--> C[Assistant gateway]
    C <--> D[AI services and context]
```

This diagram summarizes responsibility boundaries; it is not a claim that every planned behavior is accepted on physical devices.

## Engineering focus

- Keep the assistant connected to the application's user journey.
- Separate mobile behavior from the backend integration contract.
- Track build versions and distinguish emulator checks from physical-device acceptance.
- Verify that a published artifact corresponds to the version described.

## Evidence and current boundary

The [tm-apk repository](https://github.com/Ahgarzon/tm-apk) distributes pilot artifacts. It is **not the application's source-code repository**.

The integration remains a pilot. Emulator checks do not establish real-world GPS, microphone or voice behavior on every phone. This case does not claim a finished release or attribute the existing app's users to the new integration.
