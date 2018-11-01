{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Untitled0.ipynb",
      "version": "0.3.2",
      "provenance": [],
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/4070E016/Python/blob/master/googleconlab.md\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "metadata": {
        "id": "IoW00g8y0GEk",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "fe711d2d-b0dc-4414-94ef-136789a10db2"
      },
      "cell_type": "code",
      "source": [
        "# Display two messages\n",
        "print(\"Welcome to Python\") \n",
        "# print 畫\n",
        "print(\"Python is fun\")\n"
      ],
      "execution_count": 7,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Welcome to Python\n",
            "Python is fun\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "etRZAulD2QJC",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### Chapter 1\n",
        "welcome to python"
      ]
    },
    {
      "metadata": {
        "id": "Kd3el6-o4gYA",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "d8762824-1a2c-4868-e52f-07719d480f2a"
      },
      "cell_type": "code",
      "source": [
        "# Compute expression\n",
        "print((10.5 + 2 * 3) / (45 - 3.5))"
      ],
      "execution_count": 10,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "0.39759036144578314\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "U7Uw4tAv5jGj",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### Chapter 1.3 \n",
        "算術運算式"
      ]
    },
    {
      "metadata": {
        "id": "I7SNpgeM53l5",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "2155c753-e5f5-4b27-8212-69e8ebadfc03"
      },
      "cell_type": "code",
      "source": [
        "# Convert Fahrenheit to Celsius\n",
        "print(\"Fahrenheit 35 is Celsius degree \")\n",
        "print(5 / 9 * (35 - 32))\n"
      ],
      "execution_count": 12,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Fahrenheit 35 is Celsius degree \n",
            "1.6666666666666667\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "1vBttCPn7cPt",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 34
        },
        "outputId": "07308914-4f48-4481-a263-af8a716bd58e"
      },
      "cell_type": "code",
      "source": [
        "# Assign a radius\n",
        "radius = 30 # radius is now 20\n",
        "\n",
        "# Compute area\n",
        "area = radius * radius * 3.14159\n",
        "\n",
        "# Display results\n",
        "print(\"The area for the circle of radius\", radius, \"is\", area)"
      ],
      "execution_count": 14,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "The area for the circle of radius 30 is 2827.431\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "wMcLW1Ps7rtf",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### Chapter 2 \n",
        "面積 = area  \n",
        "radius 半徑"
      ]
    },
    {
      "metadata": {
        "id": "irHk9K9O8XIs",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "12c7d5b4-023f-4703-c071-0406a7e298d5"
      },
      "cell_type": "code",
      "source": [
        "# Prompt the user to enter a radius\n",
        "radius = eval(input(\"Enter a number for radius: \"))\n",
        "\n",
        "# Compute area\n",
        "area = radius * radius * 3.14159\n",
        "\n",
        "# Display results\n",
        "print(\"The area for the circle of radius\", radius, \"is\", area)"
      ],
      "execution_count": 20,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter a number for radius: 10\n",
            "The area for the circle of radius 10 is 314.159\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "tFCo41N4-LbZ",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### 2.3 \n",
        "設半徑計算面積"
      ]
    },
    {
      "metadata": {
        "id": "y9sd_RU6_QS2",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "313f4ad5-0fb3-419a-adc3-90b02a241a78"
      },
      "cell_type": "code",
      "source": [
        "# Prompt the user to enter three numbers\n",
        "number1, number2, number3 = eval(input(\n",
        "  \"Enter three numbers separated by commas: \"))\n",
        "\n",
        "# Compute average\n",
        "average = (number1 + number2 + number3) / 3\n",
        "\n",
        "# Display result\n",
        "print(\"The average of\", number1, number2, number3,\n",
        "    \"is\", average)\n"
      ],
      "execution_count": 22,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter three numbers separated by commas: 2,4,5\n",
            "The average of 2 4 5 is 3.6666666666666665\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "SKid9D8f_iaL",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### 2.4\n",
        "輸入3個數字 計算平均值\n",
        "average 平均"
      ]
    },
    {
      "metadata": {
        "id": "rJ86oVHe_txd",
        "colab_type": "code",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 51
        },
        "outputId": "2e267b9f-ad59-4c56-8f28-15ff512f6913"
      },
      "cell_type": "code",
      "source": [
        "# Prompt the user for input\n",
        "seconds = eval(input(\"Enter an integer for seconds: \"))\n",
        "\n",
        "# Get minutes and remaining seconds\n",
        "minutes = seconds // 60     # Find minutes in seconds\n",
        "remainingSeconds = seconds % 60   # Seconds remaining\n",
        "print(seconds, \"seconds is\", minutes,  \n",
        "  \"minutes and\", remainingSeconds, \"seconds\")\n"
      ],
      "execution_count": 23,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "Enter an integer for seconds: 600\n",
            "600 seconds is 10 minutes and 0 seconds\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "metadata": {
        "id": "kejq6RdDAlmd",
        "colab_type": "text"
      },
      "cell_type": "markdown",
      "source": [
        "### 2.5\n",
        "秒數除以60 換成分鐘秒"
      ]
    },
    {
      "metadata": {
        "id": "kWrxfXJXA8j6",
        "colab_type": "code",
        "colab": {}
      },
      "cell_type": "code",
      "source": [
        ""
      ],
      "execution_count": 0,
      "outputs": []
    }
  ]
}