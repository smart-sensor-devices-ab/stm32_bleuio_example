Example project for the STM32 Nucleo-144 board, on how to run the BleuIO dongle with the STM32 as a USB CDC Host.

# 1. What you will need

- A BleuIO dongle (https://www.bleuio.com/)
- STM32CubeIDE (https://www.st.com/en/development-tools/stm32cubeide.html)
- A way to connect the dongle to the Nucleo board. We used a "USB A to Micro USB B"-cable with a USB A female-to-female adapter.

# 2. How to setup project

## 2.1 Downloading the project from GitHub

Either clone the project, or download it as a zip file and unzip it, into your STM32CubeIDE workspace.

## 2.2 Deploy an Existing Project

- From STM32CubeIDE choose File>Import...>General>Existing Projects into Workspace then click 'Next >'
- Make sure you've choosen your workspace in 'Select root directory:'
- You should see the project "stm32_bleuio_example", check it and click 'Finish'.

# 3. More Info

- BleuIO Guide: [Go to Guide][1]
- BleuIO Blog: [Go to Blog][1]

  [1]: http://linktobleuioguide/
  [2]: http://linktoblog/
