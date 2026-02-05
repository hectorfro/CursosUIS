{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "setup"
      },
      "outputs": [],
      "source": [
        "import sympy as sp\n",
        "from sympy import *\n",
        "sp.init_printing() # Para que las ecuaciones se vean elegantes"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "portada"
      },
      "source": [
        "# Taller de Física con SymPy (Colaborativo)\n",
        "\n",
        "## Portada y Asignación de Roles\n",
        "\n",
        "| Rol | Estudiante Responsable | Función Principal |\n",
        "| :--- | :--- | :--- |\n",
        "| **A: El Modelador** | [Nombre Estudiante 1] | Planteamiento físico y LaTeX |\n",
        "| **B: El Programador** | [Nombre Estudiante 2] | Implementación simbólica en SymPy |\n",
        "| **C: El Analista** | [Nombre Estudiante 3] | Validación, gráficas y conclusiones |\n",
        "\n",
        "**Instrucciones de auditoría:** Cada celda debe ser editada por el responsable de su rol. El profesor verificará esto en el *Historial de Revisiones* de Colab.\n",
        "\n",
        "---"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "intro"
      },
      "source": [
        "## Introducción\n",
        "Escribe aquí una breve introducción sobre el fenómeno físico a estudiar (ej. Electromagnetismo en Física 2 u Ondas en Física 3)."
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob1_header"
      },
      "source": [
        "## Problema 1\n",
        "**Enunciado:** [Inserta aquí el problema del examen o taller]"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob1_markdown"
      },
      "source": [
        "### 1.1 Planteamiento Físico (Responsable: Estudiante A)\n",
        "Desarrolle la solución algebraica detallando las leyes físicas aplicadas (LaTeX):\n",
        "\n",
        "$$ E = \\frac{1}{4\\pi\\epsilon_0} \\int \\frac{dq}{r^2} \\hat{r} $$"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "prob1_code"
      },
      "outputs": [],
      "source": [
        "# 1.2 Solución en SymPy (Responsable: Estudiante B)\n",
        "# Defina sus símbolos y ecuaciones aquí\n"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob1_analisis"
      },
      "source": [
        "### 1.3 Validación y Análisis (Responsable: Estudiante C)\n",
        "- **Validación:** ¿El resultado de SymPy coincide con el planteamiento del Estudiante A?\n",
        "- **Análisis:** Explique qué sucede con el resultado si las variables cambian (ej. si la distancia aumenta al doble)."
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "separador1"
      },
      "source": [
        "---\n",
        "---"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob2_header"
      },
      "source": [
        "## Problema 2\n",
        "**Enunciado:** [Inserta enunciado]"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob2_markdown"
      },
      "source": [
        "### 2.1 Planteamiento Físico (Responsable: Estudiante B)\n",
        "*Nota: Los roles pueden rotar por problema si el docente lo autoriza.*"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "prob2_code"
      },
      "outputs": [],
      "source": [
        "# 2.2 Solución en SymPy (Responsable: Estudiante C)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob2_analisis"
      },
      "source": [
        "### 2.3 Validación y Análisis (Responsable: Estudiante A)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "separador2"
      },
      "source": [
        "---\n",
        "---"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob3_header"
      },
      "source": [
        "## Problema 3\n",
        "**Enunciado:** [Inserta enunciado]"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob3_markdown"
      },
      "source": [
        "### 3.1 Planteamiento Físico (Responsable: Estudiante C)"
      ]
    },
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "prob3_code"
      },
      "outputs": [],
      "source": [
        "# 3.2 Solución en SymPy (Responsable: Estudiante A)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "prob3_analisis"
      },
      "source": [
        "### 3.3 Validación y Análisis (Responsable: Estudiante B)"
      ]
    },
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "protocolo_final"
      },
      "source": [
        "---\n",
        "## Protocolo de Trabajo Colaborativo\n",
        "1. **Comunicación:** Use la función de 'Comentarios' de Colab para discutir errores.\n",
        "2. **Carga de Trabajo:** Si un integrante no aporta en 24h, los otros dos deben notificar al docente y avanzar en el cuaderno dejando constancia.\n",
        "3. **Evaluación:** La nota individual dependerá de las celdas asignadas en los roles anteriores.\n",
        "\n",
        "**F I N**"
      ]
    }
  ]
}
