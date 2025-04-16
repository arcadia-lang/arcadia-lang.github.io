# Type

Zerita has a rich type system for verbs, each one having it's own syntactic rules.
The syntax of each sentence stems from the verb and its type.
The basic syntax is VSO.
In cases that the sentence has a topic, it is placed directly after the verb.

## Linking verbs

Linking verbs are verbs that don't have an action, but rather they describe an state or a characteristic, for example "I am a doctor" or "The roses smell nice".
Syntax in zerita is verb - subject - attribute, where the attribute is in the predicative case.

1.  _olfaves tas rosesis amaresi._

    - **translation:** The roses smell sweet.

One important case in the linking verbs, is introducing oneself, as in "I'm Jon Snow".

1.  _seve de me namis jon snow_

    - **translation:** I'm Jon Snow.

## Impersonal verbs

Impersonal verbs are verbs that describe the state of the world, of a place, or even a time period.
For example they describe things like "it snows", and they lack subject and the personal suffix.

1.  _nivav._

    - **translation:** It is snowing.

## Intransitive verbs

Intransitive verbs are verbs that describe an action without a recipient, for example "the birds are singing", or, verbs that describe an state, "the cat is sleeping".
They follow the syntax verb - subject, and the subject is in the nominative case.

1.  _kantaves es avisesis._

    - **translation:** Birds are singing.

## Transitive verbs

Transitive verbs are verbs that describe an action that has a recipient, for example "I'm drinking water".
They follow the syntax verb - subject - object, the subject is in the nominative case, and the object in the accusative.
The subject can be dropped, especially in the first, second, and fourth person.

1.  _potavo e akvon._

    - **translation:** I'm drinking water.

## Distransitive verbs

Distransitive verbs are verbs that describe an action with two recipient, for example "I'm giving the book to you".
They follow the syntax verb - subject - direct object - indirect object, the subject is in the nominative case, and the direct object in the accusative and the indirect one is in the dative case.
The subject can be dropped, especially in the first, second, and fourth person.

1.  _donavo ta libron veim._

    - **translation:** I am giving the book to you.

1.  _donavo ta libron ta filim._

    - **translation:** I am giving the book to the child.

## Object promotion

Zerita allows both the direct and the indirect object to be promoted to subject.
This happens with the verb derivation system.

- **IO promotion:** "re-" prefix
- **DO promotion:** "ob-" prefix

After the promotion, the promoted argument is in nominative, and the demoted one in ablative.

1.  _potavo e akvon._

    - **translation:** I'm drinking water.

1.  _repotave e akvis meic._

    - **translation:** Water is being drunk by me.

1.  _donavo ta libron veim._

    - **translation:** I am giving the book to you.

1.  _redonave ta libris meic veim._

    - **translation:** The book is being given from me to you.

1.  _obdonavis ta libron meic._

    - **translation:** You are receiving a book from me.

## Reflexivity

In zerita reflexivity and reciprocality are handled with prefixes.
A prefix changes the verb in a reflexive or a reciprocal form.

- **reflexive:** "aut-" prefix
- **reciprocal:** "kon-" prefix

1.  _autamores adamo ete maria._

    - **translation:** Adam and Maria love themselves.

1.  _konamores adamo ete maria._

    - **translation:** Adam and Maria love each other.
