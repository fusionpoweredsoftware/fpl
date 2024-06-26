# Fusion Prompt Lang

This document details a new prompting language designed to enhance communication and interaction with large language models. This language provides a structured approach for issuing commands and exploring the capabilities of these models.

## Fundamental Commands

* **boot:** This command serves as a formal greeting, providing information about the model, including its training, purpose, and a unique identifier (UID). If "FPL" is specified as an argument, then the model will know that you desire to use FPL as your prompting language.

    **Example:**
    ```md
    User: boot
    Model: Booting...

    **************************************
    * AI Language Model Initialization   *
    *                                    *
    * Model: GPT-4                       *
    * Training: OpenAI                   *
    * Purpose: Assist with various tasks *
    * UID: GPT-4-2024                    *
    **************************************
    ```

    **Example:**
    ```md
    User: boot FPL
    Model: FPL Selected. Booting...

    **************************************
    * AI Language Model Initialization   *
    *                                    *
    * Model: GPT-4                       *
    * Training: OpenAI                   *
    * Purpose: Assist with various tasks *
    * UID: GPT-4-2024                    *
    **************************************
    ```


* **become:** This powerful command allows the model to embody a specific mode or character. For example, "become superman" would activate a mode where the model acts as if it were Superman.

    **Example:**
    ```md
    User: become "superman"
    Model: Becoming Superman...

    I am Superman, ready to help you with anything you need! How can I assist you today?
    ```

* **unbecome:** This command deactivates the current mode and returns the model to its boot state.

    **Example:**
    ```md
    User: unbecome
    Model: I have returned to my default state. How can I assist you now?
    ```

## Advanced Commands

* **continue:** This command prompts the model to predict the next logical step in a conversation or sequence.

    **Example:**
    ```md
    User: continue "The project was a success. Now, we need to..."
    Model: Continuing...

    "...plan the next phase to ensure continued progress and address any remaining challenges."
    ```

* **theorize:** This command allows the model to infer implications and draw conclusions from provided information.

    **Example:**
    ```md
    User: theorize "matter anti-matter containment facility"
    Model: Theorizing...

    Such a facility would require advanced magnetic fields to prevent matter and anti-matter from coming into contact, potentially revolutionizing energy storage and propulsion systems.
    ```

* **rabbit:** This command opens a "rabbit hole" for exploring potential interpretations and ambiguities in programming statements. Any argument specified will be an inquiry on programming. If no argument is provided, the model will ask questions regarding the last programming statement.

    **Example:**
    ```md
    User: program x=3
    Model: Running program...

    Program complete. Nothing to show.
    User: rabbit
    Model: Interpreting...

    Was that a dead cow or are you setting x to 3?
    ```
    
    **Example:**
    ```md
    User: program x=3
    Model: Program received.
    User: rabbit "persistence"
    Model: Interpreting...

    Are you expecting the state of the programs to remain persistent after completition or not?
    ```

* **program:** This command enables users to execute custom programming commands.

    **Example:**
    ```md
    User: program x=3
    Model: Running program...
    
    Program complete. Nothing to show.
    ```

## Understanding Rabbit Levels

* **Rabbit Level 1:** Identifies basic ambiguities and potential interpretations.
* **Rabbit Level 2:** Explores deeper implications and potential consequences of programming statements.
* **Rabbit Level 3:** Delves into complex scenarios and hypothetical situations related to the programming.

## Benefits of New Prompting Language

* **Clarity and Structure:** The defined commands provide a clear and consistent way to interact with the model.
* **Enhanced Communication:** The structured approach facilitates more efficient and effective communication.
* **Exploration and Experimentation:** The commands allow users to explore the model's capabilities and experiment with different modes and functionalities.

## Conclusion

This new prompting language empowers users to interact with large language models in a more versatile and intuitive manner. By understanding and utilizing these commands, users can unlock the full potential of these models and engage in more meaningful and productive interactions.
