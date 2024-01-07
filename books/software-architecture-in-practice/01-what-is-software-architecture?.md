# What Is Software Architecture?

> The software architecture is the set of structures needed to reason about the system.
> These structures comprise software elements, relations among them and properties of
> both.

- Structure: elements held together by a relation.

- Always look at the whole picture, no single element is _the_ architecture of the
  system.

- ! What is "architectural" depends on what is useful to reason about in your
  context, for your system. Different ways to look at the same system.

- Implementation details are not architectural. We abstract away the details that
  are deep in the "box" of the component. In other words, architecture cares about
  what is public in the system, not private. The box and the inputs and outputs is
  public, the inside of the box is private.

- The architecture of the system can be good or bad. System archicture != good system
  architecture.

- System arch vs Enterprise arch

  - **System arch:** cares about hardware and software components and human interactions.
    Gives enough details to reason about performance and reliability. For example: power
    consumption, weight and physical dimensions belong to the system's archicture. It's
    important to be able to find the sweet spot between software and hardware archs.
  - **Enterprise arch:** think of the organization's representation, ie, processes,
    information flow, personnel, org subunits, etc. Enterprise arch is independent of
    the computer systems involved. The question to answer is: which systems the enterprise
    should support? How software affects this?

- Software architecture must live between system and enterprise archs.
