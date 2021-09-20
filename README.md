# magic_8.cpp
First published project!

// This program is created to determine random outputs from Magic 8 Ball.

#include <iostream>
#include <cstdlib>

int main() {

  std::cout << "MAGIC 8-BALL:\n\n";

  srand(time(NULL));

  int answer = std::rand() % 10;
  
  std::cout << answer;

  if (answer == 0) {

    std::cout << " It is certain.\n";

  }
  else if (answer == 1) {

    std::cout << " Yes - definitely.\n";

  }
  else if (answer == 2) {

    std::cout << " Most likely.\n";

  }
  else if (answer == 3) {

    std::cout << " Yes.\n";

  }
  else if (answer == 4) {

    std::cout << " Ask again later.\n";

  }
  else if (answer == 5) {

    std::cout << " Better not tell you now.\n";

  }
  else if (answer == 6) {

    std::cout << " Don't count on it.\n";

  }
  else if (answer == 7) {

    std::cout << " My reply is no.\n";

  }
  else if (answer == 8) {

    std::cout << " Outlook is not good.\n";

  }
  else {

    std::cout << " Very doubtful.\n";

  }

}
