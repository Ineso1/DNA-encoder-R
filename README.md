# DNA Sequence Analysis in R

This R project includes several functions for analyzing DNA sequences. It covers the generation of random DNA sequences, calculation of sequence sizes, percentage composition of DNA bases, transcription from DNA to RNA, and the translation from RNA to a protein sequence. Additionally, it contains functions for generating the reverse and complementary strands of DNA sequences.

## Functions Included

1. `randomDNA()`: Generates a random DNA sequence of size "n".
2. `size(DNA)`: Calculates the size of a DNA sequence.
3. `porcentajes(DNA, sizeDNA)`: Prints the percentage of each base in the DNA sequence.
4. `complemento(DNA)`: Transcribes DNA to its complementary DNA sequence.
5. `transcribir(DNA)`: Transcribes DNA to RNA.
6. `traduce(i)`: Translates a three-nucleotide RNA sequence to its corresponding amino acid.
7. `traduccion_proteina(DNA)`: Translates an RNA sequence into a protein sequence.
8. `lista_inversa(lista)`: Generates the reverse sequence of the given DNA sequence.
9. `lista_complementaria(lista)`: Generates the complementary strand of a given DNA sequence.

## Usage

Each function can be called individually with the appropriate inputs. Examples are provided within the script to demonstrate the usage of each function.

![image](https://github.com/Ineso1/DNA-encoder--written-in-R-/assets/84602829/bdc232f7-d8e7-40e6-a3ae-ab1d349043b0)

### Example

```R
# Generate a random DNA sequence
ADN = randomDNA()
# Calculate the size
tam_ADN = size(ADN)
# Get the percentage of each nucleotide
porcentajes(ADN, tam_ADN)
```

Please refer to the script comments for more detailed usage instructions.

### Requirements

R environment

### Contributors
Inés Alejandro Garcia Mosqueda
Fernanda Elizabeth Romo Alarcon
César Arnaldo Cabrera Chávez
Javier Hernández Garza
José Antonio Juárez Pacheco

