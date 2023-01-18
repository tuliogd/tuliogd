```dart
import 'package:desenvolvedor/tuliogd';

void main() {
  final SobreMim perfil = SobreMim(
    nome: 'Túlio Garcia Diniz',
    area: 'Full Stack',
    trabalho: 'DinizSoft',
    local: 'Dracena/SP',
    linguagens: [
      'Dart',
      'JS',
      'TS',
      'C',
      'C#',
      'C++',
      'Delphi',
      'PHP',
    ],
  );

  print('$perfil');
}

class SobreMim extends Desenvolvedor {
  final String nome;
  final String area;
  final String trabalho;
  final String local;
  final List<String> linguagens;
  SobreMim({
    required super.nome,
    required super.area,
    required super.trabalho,
    required super.local,
    required super.linguagens,
  });

  @override
  String toString() => '(nome: $nome, area: $area, trabalho: $trabalho, '
      'local: $local, linguagens: $linguagens)';
}
```
