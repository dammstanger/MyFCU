/**------------------readme---------------------*
  * @file    ����˵���ĵ�                       *
  * @author  DammStanger                        *
  * @version V3.0.0��                           *
  * @date    2015.6.17��                       *
  * @brief   ˵����                             *
  *---------------------------------------------*

  *�����̵�оƬ��STM32RCT6                      *
  *---------------------------------------------*
  *���˽��飺                                   *
  *�����ĵ�ʱ��keil���롣                       *
  *---------------------------------------------**/
RCC_APB1PeriphClockCmd
RCC_APB1Periph_TIM2, RCC_APB1Periph_TIM3, RCC_APB1Periph_TIM4,
RCC_APB1Periph_TIM5, RCC_APB1Periph_TIM6, RCC_APB1Periph_TIM7,
RCC_APB1Periph_WWDG, RCC_APB1Periph_SPI2, RCC_APB1Periph_SPI3,
RCC_APB1Periph_USART2, RCC_APB1Periph_USART3, RCC_APB1Periph_USART4, 
RCC_APB1Periph_USART5, RCC_APB1Periph_I2C1, RCC_APB1Periph_I2C2,
RCC_APB1Periph_USB, RCC_APB1Periph_CAN1, RCC_APB1Periph_BKP,
RCC_APB1Periph_PWR, RCC_APB1Periph_DAC, RCC_APB1Periph_CEC,
RCC_APB1Periph_TIM12, RCC_APB1Periph_TIM13, RCC_APB1Periph_TIM14
RCC_APB2PeriphClockCmd
RCC_APB2Periph_AFIO, RCC_APB2Periph_GPIOA, RCC_APB2Periph_GPIOB,
  *          RCC_APB2Periph_GPIOC, RCC_APB2Periph_GPIOD, RCC_APB2Periph_GPIOE,
  *          RCC_APB2Periph_GPIOF, RCC_APB2Periph_GPIOG, RCC_APB2Periph_ADC1,
  *          RCC_APB2Periph_ADC2, RCC_APB2Periph_TIM1, RCC_APB2Periph_SPI1,
  *          RCC_APB2Periph_TIM8, RCC_APB2Periph_USART1, RCC_APB2Periph_ADC3,
  *          RCC_APB2Periph_TIM15, RCC_APB2Periph_TIM16, RCC_APB2Periph_TIM17,
  *          RCC_APB2Periph_TIM9, RCC_APB2Periph_TIM10, RCC_APB2Periph_TIM11   

��һ�棺FCU_UCOSII150609��������ģʽ
1.��������ģʽ��
2.��ԭ����Task_SonarMeasure �������Ϊ��Task_ThrottleLoop�����ڴ˽�������ģʽ�ĸ��º͸߶ȸ߼������������С�
3.������auto ����ģʽ��Ϊ�Զ���ģʽ
4.���߶ȿ�������Control����������ȡ������ǰִ�У��������յ�����������Ϊcontrol���������뺯����
5.�����ƶ��˷���ģʽ��״̬������������LED����ط���ģʽ�ı�ʾ��
6.����ʼ���������������LED���񣬲��������ģʽָʾ���ܡ�
7.��������λ�ƵĻ��ַ������Ƿ�ִ�е�if�ж��С�
8.��ң�ص�����Ƕ�ת����Control������ȡ������Add_RC_Roll��������ң�ص�����ֵ������FlyModeProcess()�е��ӵ����ƹ��̽Ƕ��С�
9.����������ǶȴӽǶȼ��㺯���磺Add_Optflow_Roll()��Add_RC_Roll()�Ⱥ�����������뺯���⡣


���棺FCU_UCOSII150617������������
