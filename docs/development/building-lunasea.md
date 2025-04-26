# :package: Building LunaSea

!!! info
	💡 **Before You Begin**  
	> Make sure you have all the necessary tools and dependencies installed.  
	  See the [requirements](./requirements/requirements.md) page for more information.

## :hammer_and_wrench: Build Instructions

1. **Clone the repository**
    ```bash
    git clone https://github.com/LunaSea-ng/LunaSea-ng@master
    cd LunaSea-ng
    ```

2. **Install dependencies**
    ```bash
    npm install
    ```

3. **Generate project files**
    ```bash
    npm run generate
    ```

4. **Build or run the app using Flutter**
    - To build for a specific platform (e.g., Android, iOS, Web):
        ```bash
        flutter build <platform>
        ```
        Replace `<platform>` with `apk`, `ios`, `web`, etc.

    - To run the app directly:
        ```bash
        flutter run
        ```
---
